# Graphics Programming
<!---->
<!--toc:start--> 
<!-- - [Graphics Programming](#graphics-programming) -->
<!--   - [Preface](#preface) -->
<!--   - [Tech Stack](#tech-stack) -->
<!--   - [Chapter 00: Building the Basics](#chapter-00-building-the-basics) -->
<!--toc:end-->
<!---->
<!-- ## Preface -->
<!---->
<!-- Hi :wave:, this is 2024  and I am in the 3rd year college.  For the last two years -->
<!-- I  have  been exploring  different  branches  of  computer science  like  graphics -->
<!-- programming, language design, linux and automation etc. Out of all those, graphics -->
<!-- programming facinated me the most as it's like learning how to become a craftsman. -->
<!-- Linux/Automation felt  like it  is all about  learning how to  use the  tools, and -->
<!-- language design... I want to build projects that normal people use and appreciate. -->
<!---->
<!-- Since I am commiting to this hobby of  mine, I want to document it, for myself and -->
<!-- for others. **OpenGL**  vs **Vulkan** vs **SDL** vs **SFML**  vs **raylib**, which -->
<!-- site  to learn  from, which  language C++  vs C,  what about  Rust. I  faced these -->
<!-- questions, and now that I spent some time  in this domain, I think I have a better -->
<!-- understanding of things to make informed decisions. -->
<!---->
<!-- See [Developer  Handbook](./chapter-00/developer-handbook/README.md) where  I note -->
<!-- down my observations and general good practices. -->
<!---->
<!-- ## Tech Stack -->
<!---->
<!-- C is  the language of  choice since all  the graphics APIs  are written in  C. The -->
<!-- choice  was also  influenced  from the  fact  that major  voices  in the  graphics -->
<!-- programming space discourage OOP and languages  like C++ which over time condition -->
<!-- the programmer's  brain to think of  the solution from the  language's perspective -->
<!-- rather than the from problem's and computer's perspective. -->
<!---->
<!-- I  would be  using the  following libraries/languages  -- [C],  [Lua], [Makefile], -->
<!-- [GLFW], [OpenGL], [Vulkan]. If you don't have any idea about any of these, :smile: -->
<!-- we are in the same :boat:. -->
<!---->
<!-- [C]: https://en.wikipedia.org/wiki/C_(programming_language) -->
<!-- [Lua]: https://lua.org/  -->
<!-- [Makefile]: https://www.gnu.org/software/make/manual/make.html -->
<!-- [GLFW]: https://www.glfw.org/ -->
<!-- [OpenGL]: https://www.opengl.org/ -->
<!-- [Vulkan]: https://www.vulkan.org/ -->
<!---->
<!-- <div style="display: flex; align-items: center;"> -->
<!-- <img style="margin-right:15px;" width=62px src="assets/c.svg" alt="c"/> -->
<!-- <img style="margin-right:15px;" width=70px; src="assets/lua.svg" alt="lua"/> -->
<!-- <img style="margin-right:15px;" width=70px src="assets/make.png" alt="make"/> -->
<!-- <img style="margin-right:15px;" width=80px; src="assets/glfw.png" alt="glfw"/> -->
<!-- <img style="margin-right:1px;" width=170px; src="assets/opengl.svg" alt="opengl"/> -->
<!-- <img style="margin-right:10px;" width=170px; src="assets/vulkan.png" alt="opengl"/> -->
<!-- </div> -->
<!---->
<!-- ## Chapter 00: Building the Basics -->
<!---->
<!-- - [A Craftsman's Understanding of Life]() -->
<!-- - [The C Programming Language](./c-programming/README.md) -->
<!-- - [GNU Make]() -->
<!-- - [Raytracing and Rasterization]() -->
<!---->
<!-- ## Chapter 01: The Graphics APIs -->
<!---->
<!-- - [Game Programming Patterns]() -->
<!-- - [SFML Blueprints]() -->
<!-- - [Computer Graphics from Scratch -- SFML Implementation]() -->
<!-- - [Learn OpenGL]() -->
<!-- - [Vulkan Graphics API]() -->
<!---->
<!-- ## Chapter 02: Getting used to the APIs -->
<!---->
<!-- - OpenGL Project 1 -- isometric blocks game (coc) -->
<!-- - OpenGL Project 2 -- fpv shooting game (IGI) -->
<!--   - use tapes and cacettes to guide the player -->
<!--   - after war/zombie setting -->
<!--   - game ai for enemies/friends etc -->
<!--   - make enemy players spawn as zombies -->
<!--   - goal is to find my father's research to cure the world -->
<!--   - father was an army doctor/researcher -->
<!-- - Vulkan Project 1 -- isometric shooting game (bomb squard) -->
<!-- - Vulkan Project 2 -- fpv block game (minecraft) -->
<!---->
<!-- ## Chapter 03: Making the Applications Extensible -->
<!---->
<!-- - Lua -- The Scripting Language -->
<!-- - extensibility approaches and best practices -->
<!-- - make project 1 2 3 4 extensible -->
<!---->
<!-- ## Chapter 04: Adding Multiplayer Support -->
<!---->
<!-- - linux networking -->
<!-- - creating a simple tcp/udp server in c -->
<!-- - server side of things/separating rendering for clients, logic for the servers -->
<!---->
<!-- ## Chapter 04: Real World Projects -->
<!---->
<!-- - [A Modern Text Editor]() -->
<!--   - client-server arciteceture based -->
<!--   - multi frame -->
<!--   - beautiful-gdb/profiler/perf via extensions -->
<!--   - mail client via extension -->
<!--   - irc/matrix/xmpp client via extension -->
<!--   - extensible gui file manager builtin via extension -->
<!--   - lsp/treesitter/coding support like neovim -->
<!--   - note taking like emacs org-roam -->
<!-- - [Village Simulator Game]() -->
<!--   - isometric village simulator -->
<!--   - game ai for the background characters/animals/bots -->
<!--   - resource and population management -->
<!--   - chemistry built in -->
<!-- - [Wayland Compositor & WindowManager]() -->
<!--   - featureful like awesome -->
<!--   - windows like, but better -->
<!---->
<!-- ----------- -->
<!-- LibreOffice VCL and VCL applications for the window manager. -->
<!-- (sync using one account on our servers) -->
<!-- - mail -->
<!-- - file-manager -->
<!-- - chat -->
