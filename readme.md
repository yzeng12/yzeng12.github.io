## Self-critique Doc

## tumblr presence project

#Yixin Zeng

#COM327

After multiple page project, I noticed I need lot improvement to achieve good view on mobile devices. 
     Change I made for mobile devices:
     In menu part (all 4 pages), the front size will be decrease, so user will not fell uncomfortable with large menu bar occupied at front of page. 
     Portrait size decrease in index, contact part when use on mobile devices.
     The media link images supposed to be small and crowed into 1 line on mobile devices, I successfully reduced pic size by media query but image margin still exist (bug need fix but fail) 

In this project, I learned a lot with haml and tumblr API use. The haml benefit for me is the format compiled to html is pretty clear and neat. And I don’t need take time and worry miss close tag. But I feel haml is not quit flexible than html. Need careful with indent, probably I’m not too feminized with it, will practice more in future.

I successfully used blog post time, blog hot, source url, hash tag and most tumblr api taught in class. But their still some bugs:
I tried use tumbler Portrait in my blog index. But something rare happen, my js file not work. I’m not sure this is cache problem or others. 
The big issue for my index is I can’t control body post style and format in my index page. Everything include picture and list in my post just simply pull by {Body}. This is insane that all picture automatically align right in my blog index page. I tried add margin:0 auto; in my img css. And define text-align: center;  in original post. one of it work finally with lot test.

