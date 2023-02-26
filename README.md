# latex-yearly-planner

NOTE: I did none of this - it is a fork from kudrykv

PDF planner designed for e-ink devices.

See [discussions](https://github.com/kudrykv/latex-yearly-planner/discussions) for available planners and their variations.

### Documentation work in progress
I am planning to write more documentation on how to use it and build it on your own.
Spoiler alert: it won't be easy.
Anyhow, more info on this will come.

## Quick Start Guide
Here are the steps to quickly get the project up and running.

* Note: if you are here just for the planners you can find pre-generated
 planners in [2022-2032 Planners Discussions](https://github.com/kudrykv/latex-yearly-planner/discussions/57).

For the tinkerers, read on.

The following was tested with [POP_OS 22.04.1 LTS](https://pop.system76.com/) under [Virtualbox](https://www.virtualbox.org/) version 6.1

### Install Dependencies
1. [Go Language](https://go.dev/dl/)
2. [LaTex](https://miktex.org/download) & [PDFLaTeX](https://www.latex-project.org/get/)
3. Note by VEronica: I used the bash build.sh command so to set the year: "bash build.sh 2023"
4. Note by VEronica: For windows users, just give up trying and use WSL to set up ubuntu on your windows machine, install git on WSL ubuntu, pull to your ubuntu drive and pretend you have a linux machine. It just works.

[Source](https://github.com/kudrykv/latex-yearly-planner/discussions/34#discussioncomment-3128344)

4. Check the "out" directory for the 'pdf' planner. To move it to your device
, follow the manufacturer's instructions on how to load a PDF on your device.

If you encounter any problems related to '.sty' files you likely need to
 install some Latex related dependencies. Copying the error and search using
  your favorite search engine should get you on track to resolving the
   dependency issues. All the best!
   
# Preview examples
<img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/01_annual.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/02_quarter.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/03_month.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/04_week.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/05_day.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/06_day_notes.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/07_day_reflect.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/08_todos_index.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/09_todos_page.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/10_notes_index.png" width="419"><img src="https://github.com/kudrykv/latex-yearly-planner/blob/main/examples/pictures/sn_a5x.planner/11_notes_page.png" width="419">
