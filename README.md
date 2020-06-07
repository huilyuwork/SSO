# SSO
 Learning SSO

 SSO - Single Sign On

 1. SSO introduction and improve user experience
    SSO sign on at one system, the other system relates this system are all signed on

 2. SSO category and implement

    same domain:  x.com -> parent domain
        web1.x.com
        web2.x.com
        web3.x.com
    cross-domain:
        weibo.com
        blog.sina.com

 3. implement steps and principle
    a. SSO -> open sign in page -> sign on and write cookies into server -> when opening another application -> server validate cookies -> yes -> continue to use
                            -> No -> return sign in page

    Key point: create cookies, save cookies, cookies exist, validate
