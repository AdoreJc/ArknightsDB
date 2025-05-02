# SpineAttachment

**Namespace:** `Spine.Unity`


## Fields

- `Boolean returnAttachmentPath`

- `Boolean currentSkinOnly`

- `Boolean placeholdersOnly`

- `String skinField`

- `String slotField`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SpineAttachment : SpineAttributeBase
{
	public Boolean returnAttachmentPath; // 0x22
	public Boolean currentSkinOnly; // 0x23
	public Boolean placeholdersOnly; // 0x24
	public String skinField; // 0x28
	public String slotField; // 0x30


	// RVA: 0x621c594 VA: 0x7598834594
	public Void .ctor(Boolean currentSkinOnly, Boolean returnAttachmentPath, Boolean placeholdersOnly, String slotField, String dataField, String skinField, Boolean includeNone, Boolean fallbackToTextField) { }
	// RVA: 0x621c68c VA: 0x759883468c
	public static Hierarchy GetHierarchy(String fullPath) { }
	// RVA: 0x621c89c VA: 0x759883489c
	public static Attachment GetAttachment(String attachmentPath, SkeletonData skeletonData) { }
	// RVA: 0x621c938 VA: 0x7598834938
	public static Attachment GetAttachment(String attachmentPath, SkeletonDataAsset skeletonDataAsset) { }
}
```