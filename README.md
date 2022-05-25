# Mypal68

A web browser aiming to backport Mozilla Quantum engine from Firefox 68 to older x86 windows OS(such as XP and Vista).

## Screenshots

![image](https://user-images.githubusercontent.com/19492771/152347482-f51058cd-2967-4bc5-80fd-5d269c328774.png)

## Installation and usage

Download from [releases directory](https://github.com/Feodor2/Mypal68/releases) and extract to a folder.
You may also run Mypal68 in portable configuration, see https://github.com/Feodor2/Mypal68/issues/67#issuecomment-1128732629.

## Compiling

-TODO-

## FAQ/Issues

- Q: What Windows versions are supported?
- A: Windows XP SP3 and higher. This browser may run on SP2 and lower, but be ready for crashes and bluescreens.
For XP, it is reccomended that you apply POSReady updates of 2019.
Do not report crashes/BSOD if you use SP2 or earlier XP.

- Q: How do I reduce RAM usage?
- A: In `about:config`, reduce `dom.ipc.processCount` value. See https://github.com/Feodor2/Mypal68/issues/6.

- Q: In Windows XP, I get bluescreen with Mypal.
- A: In `about:config`, set `browser.tabs.remote.autostart` to `false`. See https://github.com/Feodor2/Mypal68/issues/4#issuecomment-1092356432.

- Q: How do I report bugs?
- A: See below.

## Bug hunting and reporting

Please include this info into report:
- Windows version (and whether it is running 32-bit or 64-bit Windows).
- Processor and amount of RAM.
- Any specific configurations made to the browser.
- What website(s) and/or content type were attempted to be viewed if applicable.
- Whether you are running a pre-compiled binary, or a self-compiled binary (if the latter, the git revision would be especially handy).

Also:
- In case of bluescreen:
  - Do not post screenshot of bsod, as it isn't useful for troubleshooting.
  - Use http://www.nirsoft.net/utils/blue_screen_view.html and post on the attachment data report as shown in the example below.
  ![image](https://user-images.githubusercontent.com/19492771/162557875-7e17c6b9-d84a-4927-90e6-b46e5bbb44f1.png)
- In case of simple crash:
  - Please post Dr. Watson debug log. -TODO: instructions-
  - Do not post irrelevant logs.

## Disclaimer
This project does not have any direct affiliation with the upstream projects of which that it is based on, or uses libraries within. Any and all liabilities and responsibilities, including legal representation, will be solely handled by the Mypal project authors/contributors only. Other projects and organisations (namely the Mozilla Foundation as a primary contributor to much of the basis for the code) cannot and will not be held responsible for the changes made in this repository.
