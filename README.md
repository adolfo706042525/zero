# zero
Dev Home overview
Please take a few minutes to review the overview below before diving into the code:

Dashboard
The Dev Home dashboard displays Windows widgets. These widgets are built using the Windows widget platform, which relies on Adaptive Cards.

Machine configuration
The machine configuration tool utilizes the Dev Home GitHub Extension, but isn't required to clone and install apps. The app installation tool is powered by winget.

Popular apps
The machine configuration tool provides a list of popular apps when selecting applications to install. This is currently a hard-coded list of applications that have been popular with developers on Windows. Popularity was determined by high levels of installation and usage. As this is a moment in time, we are not accepting submissions for this list. We're looking to improve the experience with Suggested Apps so the list can be optimized for developers.
We are working on support for the Apple Neural Engine and the Google TPU in the accel/ folder. Eventually, we will build custom hardware for tinygrad, and it will be blindingly fast. Now, it is slow.
