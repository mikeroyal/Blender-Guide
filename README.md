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
 
5. [Vulkan Development](https://github.com/mikeroyal/Blender-Guide#vulkan-development)

6. [OpenGL Development](https://github.com/mikeroyal/Blender-Guide#opengl-development)

7. [DirectX Development](https://github.com/mikeroyal/Blender-Guide#directx-development)

8. [Metal Development](https://github.com/mikeroyal/Blender-Guide#metal-development)


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

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/104788139-401e8000-5746-11eb-9647-058dee01a00e.png">
  <br />
</p>

Including:

    - Image(JPEG, JPEG2000, PNG, TARGA, OpenEXR, DPX, Cineon, Radiance HDR, SGI Iris, TIFF)

    - Video(AVI, MPEG and Quicktime (on MacOS)).

    - 3D(Alembic, 3D Studio (3DS), COLLADA (DAE), Filmbox (FBX), Autodesk (DXF), Wavefront (OBJ), DirectX (x), Lightwave (LWO), Motion Capture (BVH), SVG, Stanford   PLY, STL, VRML, VRML97, X3D).


[Eevee](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html) is Blender???s realtime render engine built using [OpenGL]() focused on speed and interactivity while achieving the goal of rendering [PBR]() materials. Eevee can be used interactively in the 3D Viewport but also produce high quality final renders. Eevee materials are created using the same shader nodes as Cycles, making it easy to render existing scenes. For Cycles users, this makes Eevee work great for previewing materials in realtime.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/125211855-5a04cf80-e25e-11eb-94cf-f55ecf273049.png">
  <br />
</p>

**Eevee final render ??? ???Temple???. Source: [Dominik Graf](https://docs.blender.org/manual/en/latest/render/eevee/introduction.html#id2)**

[Cycles](https://www.blender.org/features/rendering/) is Blender???s ray-trace based production render engine.

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

[FreeStyle](https://docs.blender.org/manual/en/dev/render/freestyle/index.html) is an edge- and line-based non-photorealistic (NPR) rendering engine. It relies on mesh data and z-depth information to draw lines on selected edge types. Various line styles can be added to produce artistic (???hand drawn???, ???painted???, etc.) or technical (hard line) looks.

[Modifiers](https://docs.blender.org/manual/en/dev/modeling/modifiers/introduction.html) are automatic operations that affect an object in a non-destructive way. With modifiers, you can perform many effects automatically that would otherwise be too tedious to update manually (such as subdivision surfaces) and without affecting the base geometry of your object.

[UV Unwrapping](https://docs.blender.org/manual/en/latest/modeling/meshes/editing/uv/unwrapping/introduction.html) is a tool that let's you easily unwrap your mesh right inside Blender, and use image textures or paint your own directly onto the model.

[UV Sculpt](https://docs.blender.org/manual/en/dev/modeling/meshes/editing/uv/uv_sculpt.html) is a ???mode??? in Blender that allows you to grab, pinch and smooth UVs, just like Sculpt Mode.

[Dedicated Workspace](https://www.blender.org/features/sculpting/#dedicated-workspace) is a feature of sculpting organic subjects using the built-in sculpting feature set of Blender.

[Brushes](https://docs.blender.org/manual/en/latest/sculpt_paint/sculpting/introduction.html) is a feature in Blender that comes with built-in brushes such as Crease, Clay Strips, Pinch, Grab, Smooth, Mask and many more.

[Dynamic topology( dyntopo)](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/adaptive.html) is a dynamic tessellation sculpting method, which adds and removes details on the fly, whereas regular sculpting only affects the shape of a mesh.

[Masking](https://docs.blender.org/manual/en/dev/sculpt_paint/sculpting/hide_mask.html#mask) is a feature used while sculpting, areas might be hidden behind parts of the mesh or they might be too close to other parts. To work through these, it is useful to isolate parts of a mesh to sculpt on. This can be done by either completely hiding parts of the mesh or by masking areas that can not be sculpted on.

[Grease Pencil](https://www.blender.org/features/grease-pencil/) is a particular type of Blender object that allow you to draw in the 3D space. It can be use to make traditional 2D animation, cut-out animation, motion graphics or use it as storyboard tool among other things.

[Constraints](https://docs.blender.org/manual/en/2.80/animation/constraints/index.html) are a way to control an object???s properties (e.g. its location, rotation, scale), using either plain static values (like the ???limit??? ones), or another object, called ???target??? (like e.g. the ???copy??? ones).

[Drivers](https://docs.blender.org/manual/en/2.80/animation/drivers/index.html) are a way to control values of properties by means of a function, mathematical expression or small script.

[Shape keys](https://docs.blender.org/manual/en/2.80/animation/shape_keys/introduction.html) are used to deform objects into new shapes for animation. In other terminology, shape keys may be called ???morph targets??? or ???blend shapes???. The most popular use cases for shape keys are in character facial animation and in tweaking and refining a skeletal rig. They are particularly useful for modeling organic soft parts and muscles where there is a need for more control over the resulting shape than what can be achieved with combination of rotation and scale.

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

[Maya??](https://www.autodesk.com/products/maya/overview) is a 3D computer animation, modeling, simulation, and rendering software that can create realistic effects from explosions to cloth simulation.

[Maya LT???](https://www.autodesk.com/products/maya-lt/overview) is a game design software for indie game makers that can create and animate realistic-looking characters, props, and environments using the sophisticated 3D modeling and animation tools.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687226-2a682780-d1ca-11eb-9408-4b32ddc7d493.png">
  <br />
</p>

**Autodesk?? Maya. Source:[Autodesk](https://www.autodesk.com/products/maya/overview)**

[3DS Max??](https://www.autodesk.com/products/3ds-max/overview) is a 3D modeling and rendering software for design visualization, games, and animation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687233-3358f900-d1ca-11eb-8e9c-0cb68b16db0e.png">
  <br />
</p>

**Autodesk?? 3DS Max. Source:[Autodesk](https://www.autodesk.com/products/3ds-max/overview)**

[Arnold](https://www.autodesk.com/products/arnold/overview) is an advanced Monte Carlo ray tracing(Global illumination) renderer that helps you work more efficiently.

[ReCap???](https://www.autodesk.com/products/recap/overview) is a Pro 3D scanning software to transform the physical world into a digital asset. With reality capture data you can better understand and verify existing and as-built conditions to gain insights and make better decisions.

[Flame??](https://www.autodesk.com/products/flame/overview) is a 3D VFX and finishing software provides powerful tools for 3D compositing, visual effects, and editorial finishing. An integrated, creative environment means faster compositing, advanced graphics, color correction, and more.

[Mudbox??](https://www.autodesk.com/products/mudbox/overview) is a 3D digital painting and sculpting software that let's you sculpt and paint highly detailed 3D geometry and textures.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/122687228-2e944500-d1ca-11eb-894e-b55e15c35620.png">
  <br />
</p>

**Autodesk?? Mudbox. Source:[Autodesk](https://www.autodesk.com/products/mudbox/overview)**

[Character Generator??](https://www.autodesk.com/products/character-generator/overview) is a powerful 3D design and animation tools, Character Generator offers artists a web-based laboratory to create fully rigged 3D characters for animation packages and game engines.

[Smoke??](https://www.autodesk.com/products/smoke/overview) is a  video effects software helps production studios increase productivity by combining editing workflows with node-based compositing tools in a timeline-centered editing environment.

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

**[VR Scene Inspection ??? Blender Manual](https://docs.blender.org/manual/en/latest/addons/3d_view/vr_scene_inspection.html)**

[MARUI](https://www.marui-plugin.com/blender-xr/) is a plugin for Autodesk Maya that allows you to create 3D design in VR/AR for Blender.

[openXR](https://www.khronos.org/OpenXR/) is a free, open standard that provides high-performance access to Augmented Reality (AR) and Virtual Reality (VR) collectively known as XR???platforms and devices.

[Monado](https://monado.dev/) is the first OpenXR??? runtime for GNU/Linux. Monado aims to jump-start development of an open source XR ecosystem and provide the fundamental building blocks for device vendors to target the GNU/Linux platform.

[Vuforia](https://developer.vuforia.com/) is a comprehensive, scalable enterprise AR platform. Our wide-ranging solution suite ensures that we can provide the right AR technology to every customer based on their business needs.

[Vuforia Studio](https://www.ptc.com/en/products/vuforia/vuforia-studio) is a tool that allows anyone to create beautiful 3D augmented reality (AR) experiences in a matter of minutes with no coding required.

[OpenVX???](https://www.khronos.org/openvx/) is an open-source, royalty-free standard for cross platform acceleration of computer vision applications. OpenVX enables performance and power-optimized computer vision processing, especially important in embedded and real-time use cases such as face, body and gesture tracking, smart video surveillance, advanced driver assistance systems (ADAS), object and scene reconstruction, augmented reality, visual inspection, robotics and more.

[GPUImage framework](https://github.com/BradLarson/GPUImage) is a BSD-licensed iOS library that lets you apply GPU-accelerated filters and other effects to images, live camera video, and movies. In comparison to Core Image (part of iOS 5.0), GPUImage allows you to write your own custom filters, supports deployment to iOS 4.0, and has a simpler interface. However, it currently lacks some of the more advanced features of Core Image, such as facial detection.

[GPUImage3](https://github.com/BradLarson/GPUImage3) is the third generation of the [GPUImage framework](https://github.com/BradLarson/GPUImage), an open source project for performing GPU-accelerated image and video processing on Mac and iOS. The original GPUImage framework was written in Objective-C and targeted Mac and iOS, the second iteration rewritten in Swift using OpenGL to target Mac, iOS, and Linux, and now this third generation is redesigned to use Metal in place of OpenGL.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[ARCore](https://developers.google.com/ar/) is a software development kit developed by Google that allows for augmented reality applications in the real world. These tools include environmental understanding, which allows devices to detect horizontal and vertical surfaces and planes. It also includes motion tracking, which lets phones understand and track their positions relative to the world. Also ARCore???s Light Estimation API lets your digital objects appear realistically as if they???re actually part of the physical world.

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

# Vulkan Development
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129622224-8c4cca51-9200-4d70-9d16-2610d704713a.png">
  <br />
</p>

## Vulkan Learning Resources

[Vulkan??](https://www.khronos.org/vulkan/) is a modern cross-platform graphics and compute API that provides high-efficiency, cross-platform access to modern GPUs used in a wide variety of devices from PCs and consoles to mobile phones and embedded platforms. Vulkan is currently in development by the Khronos consortium.

[Khronos Group GitHub](https://github.com/KhronosGroup)

[Vulkan Documentation](https://github.com/KhronosGroup/Vulkan-Docs)

[HLSL to SPIR-V Feature Mapping Manual](https://github.com/microsoft/DirectXShaderCompiler/blob/master/docs/SPIR-V.rst)

[Vulkan GLSL Ray Tracing Emulator Tutorial](https://www.gsn-lib.org/docs/nodes/raytracing.php)

[Getting Started with Vulkan](https://vulkan-tutorial.com/)

[Vulkan Samples](https://github.com/KhronosGroup/Vulkan-Samples)

[Khronos Community Forums](https://community.khronos.org/)

## Vulkan Tools, Libraries, and Frameworks

[Vulkan SDK](https://vulkan.lunarg.com) is a set of tools that enables Vulkan developers to develop Vulkan applications.

[SPIR-V](https://www.khronos.org/spir/) is a set of tools that enables high-level language front-ends to emit programs in a standardized intermediate form to be ingested by Vulkan, OpenGL or OpenCL drivers. It eliminates the need for high-level language front-end compilers in device drivers, significantly reducing driver complexity, enables a broad range of language and framework front-ends to run on diverse hardware architectures and encourages a vibrant ecosystem of open source analysis, porting, debug and optimization tools.

[SPIRV-Reflect](https://github.com/KhronosGroup/SPIRV-Reflect) is a lightweight library that provides a C/C++ reflection API for SPIR-V shader bytecode in Vulkan applications.

[Vulkan?? Tools](https://github.com/KhronosGroup/Vulkan-Tools) is a project that provides Khronos official Vulkan Tools and Utilities for Windows, Linux, Android, and macOS.

[Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) is a API that provides a header only C++ bindings for the Vulkan C API to improve the developers Vulkan experience without introducing CPU runtime cost. It adds features like type safety for enums and bitfields, STL container support, exceptions and simple enumerations.

[Vulkan?? Memory Allocator (VMA)](https://gpuopen.com/vulkan-memory-allocator/) is a  library that provides a simple and easy to integrate API to help you allocate memory for Vulkan?? buffer and image storage.

[AMD Open Source Driver for Vulkan??](https://gpuopen.com/amd-open-source-driver-for-vulkan/) is an open-source Vulkan driver for AMD Radeon??? graphics adapters on Linux??.

[NVIDIA?? Nsight??? Visual Studio Edition](https://developer.nvidia.com/nsight-visual-studio-edition) is an application development environment for heterogeneous platforms which brings GPU computing into Microsoft Visual Studio. NVIDIA Nsight??? VSE allows you to build and debug integrated GPU kernels and native CPU code as well as inspect the state of the GPU and memory.

[Radeon??? GPU Profiler](https://gpuopen.com/rgp/) is a performance tool that can be used by developers to optimize DirectX??12, Vulkan?? and OpenCL??? applications for AMD RDNA??? and GCN hardware.

[Radeon??? GPU Analyzer](https://gpuopen.com/rga/) is a compiler and code analysis tool for Vulkan??, DirectX??, OpenGL?? and OpenCL???.

[Radeon??? Memory Visualizer (RMV)](https://gpuopen.com/rmv/) is a tool provided by AMD for use by game engine developers. It allows engineers to examine, diagnose, and understand the GPU memory management within their projects.

[DXVK](https://github.com/doitsujin/dxvk) is a Vulkan-based translation layer for Direct3D 9/10/11 which allows running 3D applications on Linux using Wine.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[RenderDoc](https://renderdoc.org) is a stand-alone graphics debugger that allows quick and easy single-frame capture and detailed introspection of any application using Vulkan, D3D11, OpenGL & OpenGL ES or D3D12 across Windows, Linux, Android, Stadia, or Nintendo Switch???.

[PerfDoc](https://github.com/ARM-software/perfdoc) is a cross-platform Vulkan layer which checks Vulkan applications for [best practices on Arm Mali](https://developer.arm.com/graphics/developer-guides/mali-gpu-best-practices) devices.

[GLFW](https://www.glfw.org/) is an Open Source, multi-platform library for OpenGL, OpenGL ES and Vulkan application development. It provides a simple, platform-independent API for creating windows, contexts and surfaces, reading input, handling events, etc. GLFW natively supports Windows, macOS and Linux and other Unix-like systems. On Linux both X11 and Wayland are supported.

[VulkanSharp](https://github.com/mono/VulkanSharp) is a project provides a .NET binding for the Vulkan API.

[Vortice.Vulkan](https://github.com/amerkoleci/Vortice.Vulkan) is a .NET Standard 2.0 and .NET5 low-level bindings for Vulkan API.

[VKD3D-Proton](https://github.com/HansKristian-Work/vkd3d-proton) is a fork of VKD3D, which aims to implement the full Direct3D 12 API on top of Vulkan.

[ImGui](https://github.com/ocornut/imgui) is a bloat-free graphical user interface library for C++. It outputs optimized vertex buffers that you can render anytime in your 3D-pipeline enabled application. It is fast, portable, renderer agnostic and self-contained (no external dependencies).

[Ash](https://github.com/MaikKlein/ash) is a very lightweight wrapper around Vulkan.

[gfx-rs](https://github.com/gfx-rs/gfx) is a low-level, cross-platform graphics and compute abstraction library in Rust.

[Vulkan.jl](https://github.com/JuliaGPU/Vulkan.jl) is a lightweight wrapper around the Vulkan graphics and compute library. It exposes abstractions over the underlying C interface, primarily geared towards developers looking for a more natural way to work with Vulkan with minimal overhead.

# OpenGL Development
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/131386211-f507b5d4-a3c9-4c21-aadd-2aa5bde94d1e.png">
  <br />
</p>

## OpenGL Learning Resources

[Open Graphics Library(OpenGL)???](https://www.opengl.org/) is an API used acrossed mulitple  programming languages and platforms for hardware-accelerated rendering of 2D/3D vector graphics currently developed by the [Khronos Group](https://www.khronos.org/).

[OpenGL ES???](https://www.khronos.org/opengles/) is the mobile subset of OpenGL for Embedded Systems(ES). It's supported on all major mobile platforms, and is also the base for WebGL.

[WebGL???](https://www.khronos.org/webgl/) is a cross-platform, royalty-free web standard for a low-level 3D graphics API based on OpenGL ES, exposed to JavaScript via the HTML5 Canvas element.

[Khronos Group | GitHub](https://github.com/KhronosGroup/)

[Khronos Technology Courses and Training](https://www.khronos.org/developers/training/)

[Top OpenGL Courses Online | Coursera](https://www.coursera.org/courses?query=opengl&amp;page=1)

[Top OpenGL Courses Online | Udemy](https://www.udemy.com/topic/opengl/)

[OpenGL Online Training Courses | LinkedIn Learning](https://www.linkedin.com/learning/topics/opengl)

[Getting Started with OpenGL](https://www.khronos.org/opengl/wiki/Getting_Started)

[OpenGL Reference Cards](https://www.khronos.org/developers/reference-cards/)

[Getting Started with OpenGL ES](https://www.khronos.org/opengles/)

[OpenGL ES Reference Cards](https://www.khronos.org/developers/reference-cards/)

[Getting Started with WebGL](https://www.khronos.org/webgl/)

[WebGL 2.0 Specification](https://www.khronos.org/registry/webgl/specs/latest/2.0/)

[WebGL Public Wiki](https://www.khronos.org/webgl/wiki)

[WebGL Reference Cards](https://www.khronos.org/developers/reference-cards/)

## OpenGL Tools, Libraries, and Frameworks

[BuGLe](https://www.opengl.org/sdk/tools/BuGLe/) is a debugger for Linux and other UNIX-like OSes. BuGLe combines a graphical OpenGL debugger with a selection of filters on the OpenGL command stream. The debugger allows viewing of state, textures, framebuffers and shaders, while the filters allow for logging, error checking, video capture and more.

[gDEBugger](https://www.opengl.org/sdk/tools/gDEBugger/) is a full-featured and free debugger and profiler representing the state-of-the-art in OpenGL and OpenGL ES debugging and profiling on  Windows and Linux.

[KTX](http://www.khronos.org/opengles/sdk/tools/KTX/) is a lightweight file format for delivering textures to OpenGL family APIs.

[RenderDoc](https://renderdoc.org) is a stand-alone graphics debugger that allows quick and easy single-frame capture and detailed introspection of any application using Vulkan, D3D11, OpenGL & OpenGL ES or D3D12 across Windows, Linux, Android, Stadia, or Nintendo Switch???.

[NVIDIA?? Nsight??? Visual Studio Edition](https://developer.nvidia.com/nsight-visual-studio-edition) is an application development environment for heterogeneous platforms which brings GPU computing into Microsoft Visual Studio. NVIDIA Nsight??? VSE allows you to build and debug integrated GPU kernels and native CPU code as well as inspect the state of the GPU and memory.

[Radeon??? GPU Profiler](https://gpuopen.com/rgp/) is a performance tool that can be used by developers to optimize DirectX??12, Vulkan?? and OpenCL??? applications for AMD RDNA??? and GCN hardware.

[Radeon??? GPU Analyzer](https://gpuopen.com/rga/) is a compiler and code analysis tool for Vulkan??, DirectX??, OpenGL?? and OpenCL???.

[AMD Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) is a powerful physically-based rendering engine that enables creative professionals to produce stunningly photorealistic images on virtually any GPU, any CPU, and any OS in over a dozen leading digital content creation and CAD applications.

[NVIDIA Omniverse](https://developer.nvidia.com/nvidia-omniverse-platform) is a powerful, multi-GPU, real-time simulation and collaboration platform for 3D production pipelines based on Pixar's Universal Scene Description and NVIDIA RTX.

[MoltenGL](https://moltengl.com) is an implementation of the OpenGL ES 2.0 API that runs on Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

[EGL](https://www.khronos.org/egl/) is an interface between Khronos rendering APIs such as OpenGL or OpenVG and the underlying native platform window system.

[Equalizer](https://www.opengl.org/sdk/libs/Equalizer/) is an open source programming interface and resource management system for scalable OpenGL applications. An Equalizer application can be deployed on any visualization system, from a singlepipe workstation to large scale graphics clusters.

[GLee](https://www.opengl.org/sdk/libs/GLee/) is a free cross-platform extension loading library that takes the burden off your application. GLee makes it easy to check for OpenGL extension and core version availability, automatically setting up the entry points with no effort on your part.

[GLEW](https://www.opengl.org/sdk/libs/GLEW/) is an open-source cross-platform extension loading library with thread-safe support for multiple rendering contexts and automatic code generation capability. GLEW provides easy-to-use and efficient methods for checking OpenGL extensions and core functionality.

[GLUS](https://www.opengl.org/sdk/libs/GLUS) is an open-source C library, which provides a hardware and operating system abstraction plus many functions usually needed for graphics programming using OpenGL, OpenGL ES or OpenVG.

[OpenGL Mathematics (GLM)](http://glm.g-truc.net/) is a C++ mathematics library for 3D software based on the OpenGL Shading Language (GLSL) specification.

[libktx](http://www.khronos.org/opengles/sdk/tools/KTX/index.php#libktx) is a library of functions(part of the [KTX tool set](http://www.khronos.org/opengles/sdk/tools/KTX)) for writing [KTX format files](http://www.khronos.org/opengles/sdk/tools/KTX/file_format_spec/) and instantiating GL textures from them.

[OpenSceneGraph](https://www.opengl.org/sdk/libs/OpenSceneGraph/) is a high-level 3D graphics toolkit exposing OpenGL's capabilities while providing many capabilities of its own. OpenSceneGraph boasts a large user community and has been employed for visual simulation, games, virtual reality, scientific visualization, and modeling.

[Mesa 3D Graphics Library](https://docs.mesa3d.org/index.html) is a project that began as an open-source implementation of the OpenGL specification. A system for rendering interactive 3D graphics. Mesa ties into several other open-source projects: the [Direct Rendering Infrastructure](https://dri.freedesktop.org/), [X.org](https://x.org/), and [Wayland](https://wayland.freedesktop.org/) to provide OpenGL support on Linux, FreeBSD, and other operating systems.

# DirectX Development
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/146693482-58c6d5d6-06ff-4ba9-b77e-38307358370d.png">
  <br />
</p>

## DirectX Learning Resources

[Microsoft DirectX??](https://support.microsoft.com/en-us/topic/how-to-install-the-latest-version-of-directx-d1f5ffa5-dae2-246c-91b1-ee1e973ed8c2) is a low-level API that handles tasks related to multimedia for game programming and video on Microsoft platforms(Windows & Xbox).

[Getting Started with DirectX 12 Ultimate](https://devblogs.microsoft.com/directx/directx-12-ultimate-getting-started-guide/)

[Getting Started with the DirectX 12 Agility SDK](https://devblogs.microsoft.com/directx/gettingstarted-dx12agility/)

[DirectX 12 and Graphics Education | YouTube](https://www.youtube.com/channel/UCiaX2B8XiXR70jaN7NK-FpA)

[DirectX??? Feature Level 12_2](https://devblogs.microsoft.com/directx/new-in-directx-feature-level-12_2/)

[DirectX 12 Technology | NVIDIA](https://www.nvidia.com/en-us/geforce/technologies/dx12/)

[AMD DirectX?? 12 (DX12) Technology | AMD](https://www.amd.com/en/technologies/directx12)

[Top Microsoft DirectX Courses Online | Udemy](https://www.udemy.com/topic/microsoft-directx/)

[DirectX - Learn Microsoft DirectX from Scratch Course | Udemy](https://www.udemy.com/course/directx-learn-microsoft-directx-from-scratch/)

[DirectX 11 Programming Course | Udemy](https://www.udemy.com/course/directx11/)

## DirectX Tools, Libraries, and Frameworks

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[DirectX-Graphics-Samples](https://github.com/Microsoft/DirectX-Graphics-Samples) is a project that contains the DirectX 12 Graphics samples that demonstrate how to build graphics intensive applications for Windows 10.

[PIX on Windows](https://devblogs.microsoft.com/pix/documentation/) is a performance tuning and debugging tool for DirectX 12 games on Windows.

[DirectStorage API](https://devblogs.microsoft.com/directx/directstorage-is-coming-to-pc/) is an API in the DirectX family originally designed for the [Velocity Architecture](https://news.xbox.com/en-us/2020/07/14/a-closer-look-at-xbox-velocity-architecture/) to Windows. The DirectX API is architected in a way that takes all this into account and maximizes performance throughout the entire pipeline from NVMe drive all the way to the GPU. It does this in several ways: by reducing per-request NVMe overhead, enabling batched many-at-a-time parallel IO requests which can be efficiently fed to the GPU, and giving games finer grain control over when they get notified of IO request completion instead of having to react to every tiny IO completion. The DirectStorage API will be available on [Windows 11](https://www.microsoft.com/en-us/windows/windows-11) PCs with NVMe SSDs, but will also be support in [Windows 10](https://www.microsoft.com/software-download/windows10) version 1909 and newer.

[NVIDIA?? Nsight??? Visual Studio Edition](https://developer.nvidia.com/nsight-visual-studio-edition) is an application development environment for heterogeneous platforms which brings GPU computing into Microsoft Visual Studio. NVIDIA Nsight??? VSE allows you to build and debug integrated GPU kernels and native CPU code as well as inspect the state of the GPU and memory.

[NVRHI (NVIDIA Rendering Hardware Interface)](https://github.com/NVIDIAGameWorks/nvrhi) is a library that implements a common abstraction layer over multiple graphics APIs (GAPIs): Direct3D 11, Direct3D 12, and Vulkan 1.2. It works on Windows (x64 only) and Linux (x64 and ARM64).

[RTXMU - RTX Memory Utility SDK](https://github.com/NVIDIAGameWorks/RTXMU) is an SDK tool that batchs up all of the acceleration structure build inputs and pass them to RTXMU which in turn will perform all the suballocation memory requests and build details including compaction. Then post build info is abstracted away by the SDK in order to do compaction under the hood. RTXMU returns acceleration structure handle ids that are used to reference the underlying memory buffers. These handle ids are passed into RTXMU to create compaction copy workloads, deallocate unused build resources or remove all memory associated with an acceleration structure.

[Radeon??? GPU Profiler](https://gpuopen.com/rgp/) is a performance tool that can be used by developers to optimize DirectX??12, Vulkan?? and OpenCL??? applications for AMD RDNA??? and GCN hardware.

[Radeon??? GPU Analyzer](https://gpuopen.com/rga/) is a compiler and code analysis tool for Vulkan??, DirectX??, OpenGL?? and OpenCL???.

[Radeon??? Memory Visualizer (RMV)](https://gpuopen.com/rmv/) is a tool provided by AMD for use by game engine developers. It allows engineers to examine, diagnose, and understand the GPU memory management within their projects.

[FNA](https://fna-xna.github.io/) is an XNA4 reimplementation that focuses solely on developing a fully accurate XNA4 runtime for the desktop.

[FAudio](https://fna-xna.github.io/) is an XAudio reimplementation that focuses solely on developing fully accurate DirectX Audio runtime libraries for the FNA project, including [XAudio2](https://docs.microsoft.com/en-us/windows/win32/xaudio2/xaudio2-introduction), [X3DAudio](https://docs.microsoft.com/en-us/windows/win32/xaudio2/x3daudio-overview), [XAPO](https://docs.microsoft.com/en-us/windows/win32/xaudio2/xapo-overview), and [XACT3](https://en.wikipedia.org/wiki/Cross-platform_Audio_Creation_Tool).

[Simple DirectMedia Layer](https://www.libsdl.org/) is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog.

[DXVK](https://github.com/doitsujin/dxvk) is a Vulkan-based translation layer for Direct3D 9/10/11 which allows running 3D applications on Linux using Wine.

[VKD3D-Proton](https://github.com/HansKristian-Work/vkd3d-proton) is a fork of VKD3D, which aims to implement the full Direct3D 12 API on top of Vulkan.

[RenderDoc](https://renderdoc.org) is a stand-alone graphics debugger that allows quick and easy single-frame capture and detailed introspection of any application using Vulkan, D3D11, OpenGL & OpenGL ES or D3D12 across Windows, Linux, Android, Stadia, or Nintendo Switch???.

# Metal Development
[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129622324-243aca6c-1feb-4b16-abef-70ad8b97f488.png">
  <br />
</p>

## Metal Learning Resources

[Metal](https://developer.apple.com/metal/) is a low-level API that provides a platform-optimized, low-overhead API for developing the latest 3D pro applications and amazing games using a rich shading language with tighter integration between graphics and compute programs. To help you do more while managing ever more complex shader code, Metal adds an unparalleled suite of advanced GPU debugging tools to help you realize the full potential of your graphics code.

**[Blender 3.1 Adds Native Metal Support in Cycles](https://wiki.blender.org/wiki/Reference/Release_Notes/3.1/Cycles)**

[Apple Developer Documentation](https://developer.apple.com/documentation)

[MetalKit](https://developer.apple.com/documentation/metalkit/)

[Metal Shading Language Specification](https://developer.apple.com/metal/Metal-Shading-Language-Specification.pdf)

[Using Metal Feature Set Tables](https://developer.apple.com/documentation/metal/gpu_features/using_metal_feature_set_tables/)

[Metal Performance Shaders](https://developer.apple.com/documentation/metalperformanceshaders/)

[Optimizing Performance with the GPU Counters Instrument](https://developer.apple.com/documentation/metal/optimizing_performance_with_the_gpu_counters_instrument?language=objc)

[Enabling Frame Capture](https://developer.apple.com/documentation/metal/frame_capture_debugging_tools/enabling_frame_capture?language=objc)

[Reducing the Memory Footprint of Metal Apps](https://developer.apple.com/documentation/metal/reducing_the_memory_footprint_of_metal_apps)

[Metal Developer Tools for Windows](https://developer.apple.com/download/release/)

[Metal Sample code](https://developer.apple.com/metal/sample-code/)

[Metal plugin for TensorFlow](https://developer.apple.com/metal/tensorflow-plugin/)

[Metal Developer discussions](https://developer.apple.com/forums/tags/metal/)

## Metal Tools, Libraries, and Frameworks

[Apple Foundation Framework](https://developer.apple.com/documentation/foundation) is a framework provides a base layer of functionality for apps and frameworks, including data storage and persistence, text processing, date and time calculations, sorting and filtering, and networking. The classes, protocols, and data types defined by Foundation are used throughout the macOS, iOS, watchOS, and tvOS SDKs.

[Apple Core Animation Framework](https://developer.apple.com/documentation/quartzcore) is a graphics rendering and animation infrastructure that provides high frame rates and smooth animations without burdening the CPU and slowing down your app.

[Apple Core Graphics Framework](https://developer.apple.com/documentation/coregraphics)is a framework based on the Quartz advanced drawing engine. It provides low-level, lightweight 2D rendering with unmatched output fidelity.

[Paravirtualized Graphics Framework](https://developer.apple.com/documentation/paravirtualizedgraphics) is a framework that implements hardware-accelerated graphics for macOS running in a virtual machine, hereafter known as the guest. The macOS operating system provides a graphics driver that runs inside the guest, communicating with the framework in the host operating system to take advantage of Metal-accelerated graphics.

[Xcode](https://developer.apple.com/xcode/) includes everything developers need to create great applications for Mac, iPhone, iPad, Apple TV, and Apple Watch. Xcode provides developers a unified workflow for user interface design, coding, testing, and debugging. Xcode 12 is built as an Universal app that runs 100% natively on Intel-based CPUs and Apple Silicon. It includes a unified macOS SDK that features all the frameworks, compilers, debuggers, and other tools you need to build apps that run natively on Apple Silicon and the Intel x86_64 CPU.

[SwiftUI](https://developer.apple.com/documentation/swiftui) is a user interface toolkit that provides views, controls, and layout structures for declaring your app's user interface. The SwiftUI framework provides event handlers for delivering taps, gestures, and other types of input to your application.

[UIKit](https://developer.apple.com/documentation/uikit) is a framework provides the required infrastructure for your iOS or tvOS apps. It provides the window and view architecture for implementing your interface, the event handling infrastructure for delivering Multi-Touch and other types of input to your app, and the main run loop needed to manage interactions among the user, the system, and your app.

[AppKit](https://developer.apple.com/documentation/appkit) is a graphical user interface toolkit that contains all the objects you need to implement the user interface for a macOS app such as windows, panels, buttons, menus, scrollers, and text fields, and it handles all the details for you as it efficiently draws on the screen, communicates with hardware devices and screen buffers, clears areas of the screen before drawing, and clips views.

[ARKit](https://developer.apple.com/augmented-reality/arkit/) is a set set of software development tools to enable developers to build augmented-reality apps for iOS developed by Apple. The latest version ARKit 3.5 takes advantage of the new LiDAR Scanner and depth sensing system on iPad Pro(2020) to support a new generation of AR apps that use Scene Geometry for enhanced scene understanding and object occlusion.

[RealityKit](https://developer.apple.com/documentation/realitykit) is a framework to implement high-performance 3D simulation and rendering with information provided by the ARKit framework to seamlessly integrate virtual objects into the real world.

[SceneKit](https://developer.apple.com/scenekit/) is a high-level 3D graphics framework that helps you create 3D animated scenes and effects in your iOS apps.

[Instruments](https://help.apple.com/instruments/mac/current/#/dev7b09c84f5) is a powerful and flexible performance-analysis and testing tool that???s part of the Xcode tool set. It???s designed to help you profile your iOS, watchOS, tvOS, and macOS apps, processes, and devices in order to better understand and optimize their behavior and performance.

[Cocoapods](https://cocoapods.org/) is a dependency manager for Swift and Objective-C used in Xcode projects by specifying the dependencies for your project in a simple text file. CocoaPods then recursively resolves dependencies between libraries, fetches source code for all dependencies, and creates and maintains an Xcode workspace to build your project.

[AppCode](https://www.jetbrains.com/objc/) is constantly monitoring the quality of your code. It warns you of errors and smells and suggests quick-fixes to resolve them automatically. AppCode provides lots of code inspections for Objective-C, Swift, C/C++, and a number of code inspections for other supported languages.

[MoltenVK](https://moltengl.com/moltenvk) is an implementation of Vulkan running on iOS and macOS using Apple's [Metal](https://developer.apple.com/metal/) graphics framework.

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Blender-Guide/pulls).


## License

[Back to the Top](https://github.com/mikeroyal/Blender-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
