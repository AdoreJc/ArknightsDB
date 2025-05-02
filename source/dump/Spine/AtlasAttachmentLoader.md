# AtlasAttachmentLoader

**Namespace:** `Spine`


## Methods

- `RegionAttachment NewRegionAttachment(Skin, String, String)`

- `MeshAttachment NewMeshAttachment(Skin, String, String)`

- `BoundingBoxAttachment NewBoundingBoxAttachment(Skin, String)`

- `PathAttachment NewPathAttachment(Skin, String)`

- `PointAttachment NewPointAttachment(Skin, String)`

- `ClippingAttachment NewClippingAttachment(Skin, String)`

- `AtlasRegion FindRegion(String)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class AtlasAttachmentLoader : AttachmentLoader
{
	private Atlas[] atlasArray; // 0x10


	// RVA: 0x61d0e64 VA: 0x75987e8e64
	public Void .ctor(Atlas[] atlasArray) { }
	// RVA: 0x61d0ee4 VA: 0x75987e8ee4
	public RegionAttachment NewRegionAttachment(Skin skin, String name, String path) { }
	// RVA: 0x61d1080 VA: 0x75987e9080
	public MeshAttachment NewMeshAttachment(Skin skin, String name, String path) { }
	// RVA: 0x61d121c VA: 0x75987e921c
	public BoundingBoxAttachment NewBoundingBoxAttachment(Skin skin, String name) { }
	// RVA: 0x61d12e4 VA: 0x75987e92e4
	public PathAttachment NewPathAttachment(Skin skin, String name) { }
	// RVA: 0x61d1348 VA: 0x75987e9348
	public PointAttachment NewPointAttachment(Skin skin, String name) { }
	// RVA: 0x61d13ac VA: 0x75987e93ac
	public ClippingAttachment NewClippingAttachment(Skin skin, String name) { }
	// RVA: 0x61d1014 VA: 0x75987e9014
	public AtlasRegion FindRegion(String name) { }
}
```