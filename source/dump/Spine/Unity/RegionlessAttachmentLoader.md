# RegionlessAttachmentLoader

**Namespace:** `Spine.Unity`


## Methods

- `RegionAttachment NewRegionAttachment(Skin, String, String)`

- `MeshAttachment NewMeshAttachment(Skin, String, String)`

- `BoundingBoxAttachment NewBoundingBoxAttachment(Skin, String)`

- `PathAttachment NewPathAttachment(Skin, String)`

- `PointAttachment NewPointAttachment(Skin, String)`

- `ClippingAttachment NewClippingAttachment(Skin, String)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class RegionlessAttachmentLoader : AttachmentLoader
{
	private static AtlasRegion emptyRegion; // 0x0

	private static AtlasRegion EmptyRegion { get; }

	// RVA: 0x61f8b40 VA: 0x7598810b40
	private static AtlasRegion get_EmptyRegion() { }
	// RVA: 0x61f8d04 VA: 0x7598810d04
	public RegionAttachment NewRegionAttachment(Skin skin, String name, String path) { }
	// RVA: 0x61f8d7c VA: 0x7598810d7c
	public MeshAttachment NewMeshAttachment(Skin skin, String name, String path) { }
	// RVA: 0x61f8df4 VA: 0x7598810df4
	public BoundingBoxAttachment NewBoundingBoxAttachment(Skin skin, String name) { }
	// RVA: 0x61f8e58 VA: 0x7598810e58
	public PathAttachment NewPathAttachment(Skin skin, String name) { }
	// RVA: 0x61f8ebc VA: 0x7598810ebc
	public PointAttachment NewPointAttachment(Skin skin, String name) { }
	// RVA: 0x61f8f20 VA: 0x7598810f20
	public ClippingAttachment NewClippingAttachment(Skin skin, String name) { }
	// RVA: 0x61f8f84 VA: 0x7598810f84
	public Void .ctor() { }
}
```