# MRToolbelt-Release
Release Repo of MRToolBelt for HoloLens 2

Inspiration
When thinking about the theme of " A new way to solve an old problem", the first thought that came into my head was the age old problem of not having the right tool with you, especially when you want to measure something small or big. Also, remembering what you measured and how you measured it can be a challenge without the right tools. Hence, I created MRToolbelt.

What it does
MRToolbelt leverages the power of Mixed Reality targeting the Microsoft HoloLens 2 and provides the user with the capability to measure items with their fingers and hands, as well as provides the ability to take photos and videos while measuring and take voice notes. It also allows the user to estimate rectangular area and the volume real world objects take up. Finally, if the user is working on say assembling a product, instead of relying on the paper manual and constantly looking down away from what they are putting together, the user can open a digital copy of the assembly manual in PDF format and have it up in their field of view for reference.

How I built it
Leveraging many of the building blocks provided in MRTK3, I started with the Hand Tracking Subsystems and one hand tracking, getting real time joint position information to be able to measure between the index and thumb and well as measuring angles between the index and thumb. From there, went to two hand measuring to be able to measure larger distances. Then to be able to measure even larger distances, leveraged Spatial Mapping and Meshing provided via AR Foundation to be able to place holographic pins on the real world environment and measure the distance, as if it was a virtual tape measure. Next, leveraging a lot of the new UX capabilities and Canvas and Non-Canvas based objects, I created a scalable rectangular measuring tool to be able to estimate area. Building on top of that as well as further use of Spatial Mapping, I constructed a way to be able to carve out an object in the Spatial Mapping mesh and estimate the volume that real world object takes up. To provide even more user friendly options, I utilized the new Speech subsystem and Phrase Recognition capabilities to provide additional functions, including opening up a Settings window where the user can set Dimensional Unit conventions, Photo/Video Capture Mode, Application Theming as well as clearing placed holograms. Also using Phrase Recognition, the user that say things like "Mark Up" to spatially place hand measurements, "Capture" to take photos, "Tape" to record video and even use Dictation to take notes. Photos, Videos, Notes and PDF files can be opened and viewed while within the MRToolbelt application as well.

Challenges we ran into
Coming up to speed quickly with all of the new features and capabilities provided by MRTK3 was a challenge. Another challenge was trying to work around things that have been present before and not present as of yet within the new MRTK, changes that have taken place, all while learning the new XRI framework on the fly and build an overall user friendly experience.

Accomplishments that we're proud of
I am especially proud of how well MRToolBelt has come out overall. Being able to learn as much as possible in such a short time frame has been a great accomplishment I am proud of.

What I learned
I learned a lot about XRI that I previously did not know about. Learned that if I set very lofty goals and challenge myself, I can achieve all of my targets and then some during development.

What's next for MRToolbelt
I would love to continue development and offer it as a useful tool to the Store for others to use as much as possible. Would love to incorporate object recognition and the ability to generate step by step instructions that anyone can use.

Built With
c#
mrtk3
openxr
unity
