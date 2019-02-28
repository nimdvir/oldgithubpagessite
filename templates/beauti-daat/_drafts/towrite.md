gadget vs addin

blog post about how to inject resources into app that need to exist only once (used in showLog and in shinyalert)

differetn ways to deploy shiny apps

what do curly braces means (on.exit, observe(), suppressstartupwarnings)

debugging shiny: options(shiny.sanitize.errors = FALSE) (`sanitize_errors false;`), `preserve_logs true`, cat, installed_packages() in UI

similar post to DO but with AWS

followup post to shiny server setup: how to develop apps/get your apps onto your server

shinymodules: what i wrote in hackfest for thibaut, plus a file input that automatically resets after upload

---

media affects what we think/talk about (ebola)

always reach higher -> youll never be satisfied/happy. happiness is wanting what you have rather than having what you want, or is happiness going after what you want?

danger with social media (fb post aug 9 2015)

stop supporting 3d movies before they'll take over and we wont' have regular movies at normal prices anymore :(

natural vs unnatural products - unnatural or modified doesn't necessarily mean bad

I often see people write code like `observeEvent(input$btn, { output$plot <- renderPlot({ ... }) })` - the correct way to do this is to just place a `input$btn` expression inside the render plot. It might look weird because what can simply accessing that value without doing anything with it do? But becuase of reactivity, just using that value makes the render plot run when the button is pressed.

-----

how to write a good shiny reproducible example?
dont use ## UI FILE .... ## SERVER FILE 
provide the sample Rmd file
provide sample data
make into bookmarkable app
find exactly where the probelm is and only share that code
