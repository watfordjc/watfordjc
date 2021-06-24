# watfordjc

I am John Cook (WatfordJC) and I go through phases of dabbling with turning fleeting thoughts into code, invariably only half finishing the code before losing interest or thinking about something else.

## ICD-10 F84.5, F33.1, F32.2

Part of the reason I leave code half finished is because of how my brain works. A lot of people on the autism spectrum have specific interests, but my combination of recurrent depressive disorder and treatment-resistant major depressive disorder mean *losing interest in things* is my psychological norm.

As a result, I have a wide range of interests, a specific interest for a period of time, and zero interests, depending on mood, meltdowns, anhedonic levels, etc. I am a domain registrar, a record label, a food grower, and the politics section of my Web site still contains my 2010 election manifesto (a week or so before the deadline for submitting nomination papers I was advised not to stand).

I wrote a list of things that didn't interest me one of the recent times I suffered anhedonia, not that I finished the list&hellip; maths, accounting, business, politics, sociology, health & fitness, first aid, psychiatry, electronics, radio communications, telecommunications, music production, Internet/Web/e-mail standards/services, video production, cosmology, computers, technology, programming.

## Projects and Applications

My Web browser acts a bit like a stack, although with more things being added to it than removed I recently tripled my RAM to avoid a figurative stack overflow. I have about 100 browser windows open and the total number of tabs is likely in the region of 500-2,000.

I do eventually close tabs when I've finished needing the documentation for coding something (or when background workers in Web pages are using too much CPU), though.

The tabs for the *Have I Been Pwned?* API were closed when I "completed" my Android app [**Bad Passwd**](https://play.google.com/store/apps/details?id=uk.johncook.android.bad_passwd), although I think the *Food Standards Agency* API tabs I had open when last working on the Android app [**Food Safety Alerts**](https://play.google.com/store/apps/details?id=uk.johncook.android.food_safety_alerts) were open on my now dead laptop so haven't been closed (yet). I prefer Java over Kotlin.

### Repositories

In the language of C, there is my [half-finished EPP client](https://github.com/watfordjc/c-epp-client-nominet) (it needs recompiling for every command), my [FCM XMPP Connection Server implementation](https://github.com/watfordjc/c-firebase-upstream-server), a half-finished [gammu MySQL PDU converter](https://github.com/watfordjc/c-sms-converter) that doesn't connect to MySQL, an [LTO encryption tool using SPTI](https://github.com/watfordjc/LTO-Encryption-SPTI), and my OBS plugin [obs-shm-image-source](https://github.com/watfordjc/obs-shm-image-source) which adds a shared memory image source type to OBS (i.e. displays a Direct3D ```ID3D11Texture2D``` stored in the GPU by another program).

In PHP, there is my unmaintained [sms_inject](https://github.com/watfordjc/sms_inject) repo that used to be able to send SMS messages using gammu with MySQL storage.

I tend to use bash/dash scripts when cobbling things together, such as [le-revoke-check-2020](https://github.com/watfordjc/le-revoke-check-2020) which checked for certificates affected by the Let's Encrypt mass revocation, and my [patches to tweet.sh](https://github.com/watfordjc/tweet.sh/branches) to allow downloading Twitter profile images from a Twitter list of users (rather than writing something that uses the API from scratch). I have many more bash/dash scripts, but they tend to have a specific purpose that wouldn't make sense to post online other than for backup purposes.

I don't really use python, although I have some [patches for tplink-smartplug](https://github.com/watfordjc/tplink-smartplug/branches), one of which is based on a gist someone wrote for the new protocol.

C# is my Windows programming language (using C and C++ when I need to such as [dabbling with DirectX](https://github.com/watfordjc/hw3d-tutorial)), although I have used WScript, COM, and ```bash.exe``` to call a bash script in WSL2 to avoid writing Windows code. [csharp-stream-controller](https://github.com/watfordjc/csharp-stream-controller) needs fixing and uses WPF and .NET Core, [LTO-Encryption-Manager](https://github.com/watfordjc/LTO-Encryption-Manager) needs finishing, and EditableCMD/[EditableCMDSanitised](https://github.com/watfordjc/EditableCMDSanitised) is a console application in .NET 5.0 that may someday be an extensible wrapper around command prompt.

### Projects

I have used GitHub repository projects in the past, but by the point I need a GitHub project to organise issues I have likely already got more than one repository the issues relate to. Rather than duplicate the issues in different repositories, they are added to the [watfordjc user project](https://github.com/watfordjc?tab=projects) that repository is linked to.

My GitHub projects usually get created when issues need prioritising, which typically occurs when the codebase has gotten to the point of needing refactoring and cleaning up.

My [**Live Streaming Control project**](https://github.com/users/watfordjc/projects/1) covers repositories about live streaming, such as my currently broken OBS stream controller.

My [**Data Backups and Archiving project**](https://github.com/users/watfordjc/projects/2) is for backing up and archiving data. As well as a Wiki containing thoughts on how I'd achieve that, it includes repositories for LTO tape storage and encryption.

My [**EditableCMD project**](https://github.com/users/watfordjc/projects/3) is for my command prompt wrapper with editable output and plugin support.
