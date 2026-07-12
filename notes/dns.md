Jb hum kisi website pr jaty hain to wahan pr jb domain jesy scrimba.com type kr enter hit krty hain to DNS (Domain Name system) humari device sy mtlb humari local machine k cache leya hai and if its is fail to wo Recursive Resolver ko bolta hai jo k huamra ISP (Interent Service Provider ) hota hai mtlb ye wahi hota hai jo humy net provide krta hai jesy humary ghr mr PTCL wiif hai to oska service provider he humara ISP hai jo k mainly Pakistan Telecomunication hota hai jo provide kr rha hota hai ; to Jb local Cache sy IP nhi milta to wo osy ISP ( Recursive Resolver ) k pass ja kr check krta hai mtlb humara ISP ye janta hai k hum konsi website dekh hry hain login kr rhy hain search kr rhy Q key humara browser her bar osky pass ja IP ki request krta hai takey wo Website ko show kr sky 
lkn ISP be sb data apny pass nhi rekh kr betha hota , resolver ka apna ans be oski apni he cache me hota hai agr osky pass data huwa oski cache  me to wo direct local machine ko IP snd kr deyta hai agr nahi ? to wo aik method follow krta hai
to wo phir root server k pass jata hai root server he index yani main server hota hai sary connect k beach me lkn isky pass be right IP nhi hota to ye bs itna janta hai konsi domain ko konsa server handle kr rha hai jesy he
inki baat hui apes me 

Recursive Resolver : "Hey Root Server who handles .com ? "

Root Server : "This TLD server 192.0.2.10 handles .com "

then he gose to 
Recursive Resolver : "Hey TLD server who handle scrimba.com "
TLD server : " this authoritative server 203.0.113.53 handles scrimba.com!"

then he gose to 
Recursive Resolver : " hey authoritative what is the IP of scrimba.com"

Authoritative Sevre : " k pass ns.scrimba.com (ns means name service)  hoti hai to wo osy return kr deyta hai resolver ko"

or finaly resolver client machine to bta deyta hai ye hai iska IP or client machine scrimba.com ko humary web browser pr show kr deyti hai!