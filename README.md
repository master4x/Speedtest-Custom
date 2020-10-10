# Speedtest-Custom
An embedded website for your SPEEDTEST CUSTOM™ by Ookla to run from GitHub with your own domain!

## Setup Guide

1. Head to https://www.ookla.com/speedtest-custom and click on 'Start for Free'

2. Create an account with your preferred license and personal data

3. Login to your account https://account.ookla.com

4. Go to 'Speedtest Custom' and allow cookies for the website

5. Give the Speedtest a *custom subdomain* (Test URL) and enable HTTPS

> Ookla does not allow *speedtest*.EXAMPLE.COM or *test*.EXAMPLE.COM

6. Customize your Speedtest in the 'Interface' tab

7. In the 'Servers' tab you can now select your own servers, if available

8. Now add your domain/subdomain (or GitHub subdomain) to your test under 'Embed'

> Example: add '**username**.github.io', replace **username** with your GitHub username

9. Press 'Save & Publish' in the top right corner

10. Your Speedtest is now ready and is reachable via the *.speedtestcustom.com* subdomain from *step 5*

> To publish the Speedtest under your own domain follow these steps

11. Fork this repository with the button in the top right corner

12. Open and edit the `index.html` file

13. Change the <iframe src="https://CHANGEME.speedtestcustom.com/"... URL to your subdomain from *step 5*

14. Save the file and exit the editor

15. Go into the settings of the forked repository and scroll down to 'GitHub Pages'

16. As the website source, select the 'master' branch and hit 'save'

17. After this GitHub should show up your new subdomain with *.github.io*

18. Now add your Custom domain in the field below and save again

19. Make sure you have added your domain to your control panel in *step 8* already

20. Route your Domain DNS with A-RECORDs to the GitHub servers to complete the setup
```
EXAMPLE.COM     3600    A     185.199.108.153
EXAMPLE.COM     3600    A     185.199.109.153
EXAMPLE.COM     3600    A     185.199.110.153
EXAMPLE.COM     3600    A     185.199.111.153
```

#### License
This code is under MIT license.

Copyright 2020 github.com/master4x

----

**Free Code!**
