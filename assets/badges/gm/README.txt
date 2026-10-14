Original GM badge source images

FF_UI_Badge_GM.png             41 x 47 pixels, transparent RGBA
FF_ingame_hud_Badge_GM.png     26 x 29 pixels, transparent RGBA

Extracted from Free Fire MAX 2.121.1 using the exact named atlas rectangles.
RGB and alpha were reconstructed according to the original split-alpha shader.
No resizing, AI generation, redrawing or replacement artwork was used.
See manifest.json for source identity, dimensions and SHA256 hashes.

Resource package
These source PNGs are also packaged in assets/android/1.56.10, in the bundle
ui/atlas/hotfix/ui_chrono_gm_badges. It uses the original Unity 5.6.3f1 /
serialized 17 UIAtlas script, material and shader. Split RGBA32 textures retain
the original sprite pixels exactly. Both sprites are registered in resconf,
the AssetBundle manifest and compulsory fileinfo. Twenty-two prior payloads
are unchanged; the old 1.56.9 resource directory is preserved.

The local live/ver.php points to 1.56.10. Publish the resource files and version
pointer together to announce the compulsory download. The source PNGs in this
folder themselves are not downloaded as standalone files by the client.

Rendering limitation
This package registers downloadable images; it is not an activated GM F fix.
Client 1.56.1's traced profile/HUD badge checks still reject native GM role 1.
An atlas entry does not change that check or enable a separate GM F badge.
No supported existing component or code-hotfix route has been established.
The Influencer V badge, account roles, APK, native library and client code are
unchanged. Client download and gameplay rendering remain unverified.
