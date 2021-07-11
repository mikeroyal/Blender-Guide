<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211848-53765800-e25e-11eb-872d-732aa2e74ad1.png">
  <br />
  Blender Guide
</h1>

#### A guide covering Blender including the applications, libraries and tools that will make you a better and more efficient Designer/Developer with Blender.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/125211853-58d3a280-e25e-11eb-989b-8ca8817443e3.png">
  <br />
</p>

# Table of Contents

1. [Blender Learning Resources](https://github.com/mikeroyal/Blender-Guide#Blender-Learning-Resources)

2. [Blender Tools and Addons](https://github.com/mikeroyal/Blender-Guide#Blender-Tools-and-Addons)

3. [3D Graphics Tools, Libraries, and Frameworks](https://github.com/mikeroyal/Blender-Guide#3D-Graphics-Tools-Libraries-and-Frameworks)

4. [Augmented Reality (AR) & Virtual Reality (VR)](https://github.com/mikeroyal/Blender-Guide#augmented-reality-ar--virtual-reality-vr)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/104788139-401e8000-5746-11eb-9647-058dee01a00e.png">
  <br />
</p>

**Compositing a 3D scene in Blender. Source:[Blender](https://www.blender.org/features/vfx/)**

## Blender Learning Resources
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

[Blender](https://www.blender.org) is a professional, free and open-source 3D computer graphics software toolset used for creating animated films, visual effects, art, 3D printed models, interactive 3D applications and video games. [Independent Blender LTS support and services for enterprises](https://www.blender.org/press/canonical-offering-blender-support/) are available now via [Canonical](https://canonical.com/)(makers of the Ubuntu Advanced platform).

[Blender 2.93 Reference Manual](https://docs.blender.org/manual/en/latest/index.html)

[Blender Documentation](https://docs.blender.org/)

[Blender Foundation](https://www.blender.org/foundation/)

[Blender Community Fourm](https://devtalk.blender.org/)

[Blender Foundation Certification Training](https://www.blender.org/certification/)

[Blender Cloud Courses](https://cloud.blender.org/courses)

[Blender Institute](https://www.blender.org/institute/)

[Blender Demo Project files](https://www.blender.org/download/demo-files/)

[Blender YouTube Tutorials and Demos](https://www.youtube.com/user/BlenderFoundation)

[Blender Donations & Sponsors](https://www.blender.org/foundation/donation-payment/)

[Blender Education](https://www.blender.org/get-involved/)

[Blender Network](https://www.blendernetwork.org/)

[Blender Courses from Udemy](https://www.udemy.com/topic/blender/)

[BlenderNation](https://www.blendernation.com/category/blender/add-ons/)

[Blender Market(The indie market for Blender creators)](https://www.blendermarket.com/categories/scripts-and-addons)

## Blender Tools and Addons
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

[Blender](https://www.blender.org) comes packed with import/export support for many different programs.

Including:

    - Image(JPEG, JPEG2000, PNG, TARGA, OpenEXR, DPX, Cineon, Radiance HDR, SGI Iris, TIFF)

    - Video(AVI, MPEG and Quicktime (on MacOS)).

    - 3D(Alembic, 3D Studio (3DS), COLLADA (DAE), Filmbox (FBX), Autodesk (DXF), Wavefront (OBJ), DirectX (x), Lightwave (LWO), Motion Capture (BVH), SVG, Stanford   PLY, STL, VRML, VRML97, X3D).


[Eevee](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html) is Blender’s realtime render engine built using [OpenGL]() focused on speed and interactivity while achieving the goal of rendering [PBR]() materials. Eevee can be used interactively in the 3D Viewport but also produce high quality final renders. Eevee materials are created using the same shader nodes as Cycles, making it easy to render existing scenes. For Cycles users, this makes Eevee work great for previewing materials in realtime.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211855-5a04cf80-e25e-11eb-94cf-f55ecf273049.png">
  <br />
</p>

**Eevee final render – “Temple”. Source:[Dominik Graf](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html#id2)**

[Cycles](https://www.blender.org/features/rendering/) is Blender’s ray-trace based production render engine.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338215-6ec91f00-b4ca-11eb-9c9e-f5cf377ca3c4.png">
  <br />
</p>

 **Blender's Cycles Render Engine. Source: [Blender](https://www.blender.org)**

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118338217-6ffa4c00-b4ca-11eb-92d0-9aa30230495d.png">
  <br />
</p>

 **Blender VFX(Visual Effects). Source: [Blender](https://www.blender.org)**

[FreeStyle](https://docs.blender.org/manual/en/dev/render/freestyle/index.html) is an edge- and line-based non-photorealistic (NPR) rendering engine. It relies on mesh data and z-depth information to draw lines on selected edge types. Various line styles can be added to produce artistic (“hand drawn”, “painted”, etc.) or technical (hard line) looks.

[Modifiers](https://docs.blender.org/manual/en/dev/modeling/modifiers/introduction.html) are automatic operations that affect an object in a non-destructive way. With modifiers, you can perform many effects automatically that would otherwise be too tedious to update manually (such as subdivision surfaces) and without affecting the base geometry of your object.

[UV Unwrapping](https://docs.blender.org/manual/en/latest/modeling/meshes/editing/uv/unwrapping/introduction.html) is a tool that let's you easily unwrap your mesh right inside Blender, and use image textures or paint your own directly onto the model.

[UV Sculpt](https://docs.blender.org/manual/en/dev/modeling/meshes/editing/uv/uv_sculpt.html) is a “mode” in Blender that allows you to grab, pinch and smooth UVs, just like Sculpt Mode.

[Dedicated Workspace](https://www.blender.org/features/sculpting/#dedicated-workspace) is a feature of sculpting organic subjects using the built-in sculpting feature set of Blender.

[Brushes](https://docs.blender.org/manual/en/latest/sculpt_paint/sculpting/introduction.html) is a feature in Blender that comes with built-in brushes such as Crease, Clay Strips, Pinch, Grab, Smooth, Mask and many more.

[Dynamic topology( dyntopo)](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/adaptive.html) is a dynamic tessellation sculpting method, which adds and removes details on the fly, whereas regular sculpting only affects the shape of a mesh.

[Masking](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/hide_mask.html#mask) is a feature used while sculpting, areas might be hidden behind parts of the mesh or they might be too close to other parts. To work through these, it is useful to isolate parts of a mesh to sculpt on. This can be done by either completely hiding parts of the mesh or by masking areas that can not be sculpted on.

[Grease Pencil](https://www.blender.org/features/grease-pencil/) is a particular type of Blender object that allow you to draw in the 3D space. It can be use to make traditional 2D animation, cut-out animation, motion graphics or use it as storyboard tool among other things.

[Constraints](https://docs.blender.org/manual/en/2.80/animation/constraints/index.html) are a way to control an object’s properties (e.g. its location, rotation, scale), using either plain static values (like the “limit” ones), or another object, called “target” (like e.g. the “copy” ones).

[Drivers](https://docs.blender.org/manual/en/2.80/animation/drivers/index.html) are a way to control values of properties by means of a function, mathematical expression or small script.

[Shape keys](https://docs.blender.org/manual/en/2.80/animation/shape_keys/introduction.html) are used to deform objects into new shapes for animation. In other terminology, shape keys may be called “morph targets” or “blend shapes”. The most popular use cases for shape keys are in character facial animation and in tweaking and refining a skeletal rig. They are particularly useful for modeling organic soft parts and muscles where there is a need for more control over the resulting shape than what can be achieved with combination of rotation and scale.

[Motion Paths](https://docs.blender.org/manual/en/2.80/animation/motion_paths.html) is a tool allows you to visualize the motion of points as paths over a series of frames. These points can be object origins and bone joints.

[Simulations](https://www.blender.org/features/simulation/) is a tool that allows you to create amazing Simulations such as a crumbling building, rain, fire, smoke, fluid, cloth or full on destruction.

[Blender Video Editor](https://www.blender.org/features/video-editing/) is a video editor that comes with a built-in video sequence editor allows you to perform basic actions like video cuts and splicing, as well as more complex tasks like video masking or color grading.

[Blender Compositing](https://www.blender.org/features/vfx/#compositing) is a feature that comes with an impressive library of nodes for creating camera fx, color grading, vignettes and much more
Render-layer support. Along with the ability to render to multiLayer OpenEXR files.

[Blender Motion Tracking](https://www.blender.org/features/vfx/#motion-tracking) is a feature that provides production ready camera and object tracking, allowing you to import raw footage, track it, mask areas and reconstruct the camera movements live in your 3d scene.

[fSpy](https://fspy.io) is an open source still image [camera matching tool](https://learn.foundry.com/modo/content/help/pages/rendering/camera_matching.html) developed by Stuffmatic. Also check-out the fSpy importer for [Blender](https://www.blender.org/).

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211857-5c672980-e25e-11eb-93d5-ac8e0069298d.png">
  <br />
</p>

**Using the fSpy in Blender for Camera Matching a 3D model. Source:[fSpy](https://fspy.io/)**


## 3D Graphics Tools, Libraries and Frameworks
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

[Maya®](https://www.autodesk.com/products/maya/overview) is a 3D computer animation, modeling, simulation, and rendering software that can create realistic effects from explosions to cloth simulation.

[Maya LT™](https://www.autodesk.com/products/maya-lt/overview) is a game design software for indie game makers that can create and animate realistic-looking characters, props, and environments using the sophisticated 3D modeling and animation tools.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687226-2a682780-d1ca-11eb-9408-4b32ddc7d493.png">
  <br />
</p>

**Autodesk® Maya. Source:[Autodesk](https://www.autodesk.com/products/maya/overview)**

[3DS Max®](https://www.autodesk.com/products/3ds-max/overview) is a 3D modeling and rendering software for design visualization, games, and animation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687233-3358f900-d1ca-11eb-8e9c-0cb68b16db0e.png">
  <br />
</p>

**Autodesk® 3DS Max. Source:[Autodesk](https://www.autodesk.com/products/3ds-max/overview)**

[Arnold](https://www.autodesk.com/products/arnold/overview) is an advanced Monte Carlo ray tracing(Global illumination) renderer that helps you work more efficiently.

[ReCap™](https://www.autodesk.com/products/recap/overview) is a Pro 3D scanning software to transform the physical world into a digital asset. With reality capture data you can better understand and verify existing and as-built conditions to gain insights and make better decisions.

[Flame®](https://www.autodesk.com/products/flame/overview) is a 3D VFX and finishing software provides powerful tools for 3D compositing, visual effects, and editorial finishing. An integrated, creative environment means faster compositing, advanced graphics, color correction, and more.

[Mudbox®](https://www.autodesk.com/products/mudbox/overview) is a 3D digital painting and sculpting software that let's you sculpt and paint highly detailed 3D geometry and textures.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687228-2e944500-d1ca-11eb-894e-b55e15c35620.png">
  <br />
</p>

**Autodesk® Mudbox. Source:[Autodesk](https://www.autodesk.com/products/mudbox/overview)**

[Character Generator®](https://www.autodesk.com/products/character-generator/overview) is a powerful 3D design and animation tools, Character Generator offers artists a web-based laboratory to create fully rigged 3D characters for animation packages and game engines.

[Smoke®](https://www.autodesk.com/products/smoke/overview) is a  video effects software helps production studios increase productivity by combining editing workflows with node-based compositing tools in a timeline-centered editing environment.

[ShotGrid](https://www.autodesk.com/products/shotgrid/overview) formerly Shotgun Software, is software for creative project management software and review tools for film, TV, and games that streamlines workflows for creative studios.

[Open Graphics Library(OpenGL)](https://www.opengl.org/) is an API used acrossed mulitple  programming languages and platforms for hardware-accelerated rendering of 2D/3D vector graphics currently developed by the [Khronos Group](https://www.khronos.org/).

[Open Computing Language (OpenCL)](https://www.khronos.org/opencl/) is an open standard for [parallel programming](https://www.coursera.org/lecture/parprog1/introduction-to-parallel-computing-zNrIS) of heterogeneous platforms consisting of CPUs, GPUs, and other hardware accelerators found in supercomputers, cloud servers, personal computers, mobile devices and embedded platforms.

[OpenGL Shading Language(GLSL)](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL)) is a High Level Shading Language based on the C-style language, so it covers most of the features a user would expect with such a language.  Such as control structures (for-loops, if-else statements, etc) exist in GLSL, including the switch statement.

[High Level Shading Language(HLSL)](https://docs.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl) is the High Level Shading Language for DirectX. Using HLSL, the user can create C-like programmable shaders for the Direct3D pipeline. HLSL was first created with DirectX 9 to set up the programmable 3D pipeline.

[DirectX 12 Ultimate](https://github.com/Microsoft/DirectX-Graphics-Samples) is an API(for high performance 2D & 3D graphics) from Microsoft. DirectX 12 Ultimate brings support for ray tracing, mesh shaders, variable rate shading, and sampler feedback. Available in Windows 2004 version(May 2020 Update).

[Vulkan](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Metal](https://developer.apple.com/metal/) is a low-level GPU programming framework used for rendering 2D and 3D graphics on Apple platforms such as iOS, iPadOS, macOS, watchOS and tvOS.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

[OpenGL ES](https://www.khronos.org/opengles/) is the mobile subset of OpenGL. It's supported on all major mobile platforms, and is also the base for WebGL.

[OpenCL](https://www.khronos.org/opencl/) is a framework for writing programs that execute across heterogeneous platforms consisting of CPUs, GPUs, DSPs, FPGAs and other processors or hardware accelerators.

[EGL](https://www.khronos.org/egl/) is an interface between Khronos rendering APIs such as OpenGL or OpenVG and the underlying native platform window system.

[VDPAU](https://www.freedesktop.org/wiki/Software/VDPAU/) is the Video Decode and Presentation API for UNIX. It provides an interface to video decode acceleration and presentation hardware present in modern GPUs.

[VA API](https://freedesktop.org/wiki/Software/vaapi/) is an open-source library and API specification, which provides access to graphics hardware acceleration capabilities for video processing.

[XvMC](https://en.wikipedia.org/wiki/X-Video_Motion_Compensation) is an extension of the X video extension (Xv) for the X Window System. The XvMC API allows video programs to offload portions of the video decoding process to the GPU hardware.

[LibGDX](https://github.com/libgdx/libgdx) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

# Augmented Reality (AR) & Virtual Reality (VR)
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

**[VR Scene Inspection — Blender Manual](https://docs.blender.org/manual/en/latest/addons/3d_view/vr_scene_inspection.html)**

[MARUI](https://www.marui-plugin.com/blender-xr/) is a plugin for Autodesk Maya that allows you to create 3D design in VR/AR for Blender.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR—platforms and devices.

[Monado](https://monado.dev/) is the first OpenXR™ runtime for GNU/Linux. Monado aims to jump-start development of an open source XR ecosystem and provide the fundamental building blocks for device vendors to target the GNU/Linux platform.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[ARCore](https://developers.google.com/ar/) is a software development kit developed by Google that allows for augmented reality applications in the real world. These tools include environmental understanding, which allows devices to detect horizontal and vertical surfaces and planes. It also includes motion tracking, which lets phones understand and track their positions relative to the world. Also ARCore’s Light Estimation API lets your digital objects appear realistically as if they’re actually part of the physical world.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720758-e843d300-b193-11eb-9796-bde15aebed71.png">
<br />
</p>

Microsoft HoloLens Headset. Source: [Microsoft](https://www.microsoft.com/en-us/hololens/buy)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720763-e9750000-b193-11eb-888a-e4bccd6c30eb.png">
<br />
</p>

PlayStation VR Headset. Source: [PlayStation](https://www.playstation.com/en-us/ps-vr/)

[SteamVR](https://store.steampowered.com/steamvr) is the ultimate tool for experiencing VR content on the hardware of your choice. SteamVR supports the Valve Index, HTC Vive, Oculus Rift, Windows Mixed Reality headsets, and others.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110881514-543db400-8295-11eb-9543-fd5d385ddb05.png">
<br />

SteamVR Home
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/117720776-ed088700-b193-11eb-8538-9831999b5104.png">
<br />
</p>
Valve Index VR Headset. Source: [Steam](https://store.steampowered.com/valveindex)


[OpenVR](https://github.com/ValveSoftware/openvr) is an API and runtime that allows access to VR hardware(Steam Index, HTC Vive, and Oculus Rift) from multiple vendors without requiring that applications have specific knowledge of the hardware they are targeting.

[OpenVR Benchmark on Steam](https://store.steampowered.com/app/955610/OpenVR_Benchmark/) is the first benchmark tool for reproducibly testing your real VR performance, rendering inside of your VR headset.

[OpenHMD](http://www.openhmd.net/) is open source API and drivers that supports a wide range of HMD(head-mounted display) devices such as Oculus Rift, HTC Vive, Sony PSVR, and others.

[Libsurvive](https://github.com/cntools/libsurvive) is a set of tools and libraries that enable 6 dof tracking on lighthouse and vive based systems that is completely open source and can run on any device. It currently supports both SteamVR 1.0 and SteamVR 2.0 generation of devices and should support any tracked object commercially available.

[Simula](https://github.com/SimulaVR/Simula) is a VR window manager for Linux that runs on top of Godot. It takes less than 1 minute to install. Simula is officially compatible with SteamVR headsets equipped with Linux drivers (e.g. HTC Vive, HTC Vive Pro, & Valve Index). We have also added experimental support to OpenXR headsets that have Monado drivers (e.g. North Star, OSVR HDK, and PSVR). Some people have gotten the Oculus Rift S to run Simula via OpenHMD ([see here](https://github.com/OpenHMD/OpenHMD/issues/225#issuecomment-638454156)).


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Blender-Guide/pulls).


## License

[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
