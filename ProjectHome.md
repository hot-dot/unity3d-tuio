# Cut down TUIO framework for Unity3d from Mindstorm #

**NOTE: Unity 4.3 has a new definition for UnityEngine.Touch.  Please use the latest version from SVN if you are using Unity 4.3.**

Unity3d-TUIO is a library for using TUIO input in Unity3d.  Tuio input is accessible in the same way as iPhone and Android touch data (UnityEngine.Touch objects).

Also included is the MindstormGestures framework to turn that touch data into interactions with objects.  MindstormGestures includes 4 examples projects to get you started.

To use Tuio input in your project just change:

```
foreach (Touch t in Input.touches)
{
    // Process your touch information here
}
```

To:

```
foreach (Touch t in TuioInput.touches)
{
    // Process your touch information here
}
```

### What's in the box ###

  * MindstormGestures and MindstormTuio packages (ready for import into your project)

  * Project with MindstormGestures, MindstormTuio and examples ready to run

  * 4 Example scenes showing use of MindstormGestures (including Photo Browser)

  * Full source code comments

  * **NEW** - Supports Windows 8 Store applications (Native touch and TUIO)

  * **NEW** - GUITexture buttons example scene added

  * TUIO 1.0 Receiver (works with <a href='http://ccv.nuigroup.com/'>CCV</a>, <a href='http://www.nuigroup.com/touchlib/'>TouchLib</a>, and more)

#### Fully Open Source (all of it, under LGPL) ####

  * All code included

  * No 3rd Party dependencies whatsoever (apart from Unity3D of course)

#### Professionally supported ####

  * Project is supported by [Mindstorm](http://www.mindstorm.com) for the purpose of getting more people developing multi-touch applications.

![https://lh3.googleusercontent.com/-lHhBbkv8zog/URD2G4aj1QI/AAAAAAAAAQI/F-xicwMVPsc/s400/Cannon.png](https://lh3.googleusercontent.com/-lHhBbkv8zog/URD2G4aj1QI/AAAAAAAAAQI/F-xicwMVPsc/s400/Cannon.png)

<sub>Cannon Example</sub>

![https://lh4.googleusercontent.com/-3zpZTM4vpr8/URD2GwB8IpI/AAAAAAAAAQE/i95OLlj6w1A/s400/Dragables.png](https://lh4.googleusercontent.com/-3zpZTM4vpr8/URD2GwB8IpI/AAAAAAAAAQE/i95OLlj6w1A/s400/Dragables.png)

<sub>Dragable Example</sub>

![https://lh6.googleusercontent.com/-aLKpyGGKKbM/URD2HRM0rKI/AAAAAAAAAQM/e9G40ZweMIY/s400/PhotoBrowser.png](https://lh6.googleusercontent.com/-aLKpyGGKKbM/URD2HRM0rKI/AAAAAAAAAQM/e9G40ZweMIY/s400/PhotoBrowser.png)

<sub>Photo Browser Example</sub>

![https://lh3.googleusercontent.com/-apJSLbggJkw/URD2KEYiDkI/AAAAAAAAAQc/ZTaUner6weo/s400/Spawner.png](https://lh3.googleusercontent.com/-apJSLbggJkw/URD2KEYiDkI/AAAAAAAAAQc/ZTaUner6weo/s400/Spawner.png)

<sub>Spawner Example</sub>