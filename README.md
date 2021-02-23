# Stopping DNS Rebinding Attacks in the Browser

- Abstract
DNS rebinding attacks circumvent the same-origin policy of browsers and severely jeopardize user privacy. 
Although recent studies have shown that DNS rebinding attacks pose severe security threats to users, up to
now little effort has been spent to assess the effectiveness of known solutions to prevent such attacks. We have
carried out such a study to assess the protective measures proposed in prior studies. We found that none of
the recommended techniques can entirely halt this attack due to various factors, e.g., network layer encryption
renders packet inspection infeasible. Examining the previous problematic factors, we realize that a protective
measure must be implemented at the browser-level. Therefore, we propose a defensive measure, a browser
plug-in called Fail-rebind, that can detect, inform, and protect users in the event of an attack. Afterwards, we
discuss the merits and limitations of our method compared to prior methods. Our ﬁndings suggest that Failrebind
does not necessitate expert knowledge, works on different OSes and smart devices, and is independent
of networks and location.