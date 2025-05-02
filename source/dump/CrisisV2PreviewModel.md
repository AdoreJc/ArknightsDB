# CrisisV2PreviewModel

**Namespace:** ` `


## Fields

- `CrisisV2PreviewInfo m_previewInfo`

- `Int32 m_hidePreviewSeqNum`


## Properties

- `Int32 hidePreviewSeqNum`


## Methods

- `Int32 get_hidePreviewSeqNum()`

- `Void UpdatePreview(CrisisV2PreviewInfo)`

- `Int32 HidePreview()`

- `CrisisV2PreviewInfo GetPreviewInfo()`

- `Boolean IsInPreview()`

- `Boolean NeedHighLight(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2PreviewModel : IHotfixable
{
	private CrisisV2PreviewInfo m_previewInfo; // 0x10
	private Int32 m_hidePreviewSeqNum; // 0x48
	private static DelegateBridge __Hotfix0_get_hidePreviewSeqNum; // 0x0
	private static DelegateBridge __Hotfix0_UpdatePreview; // 0x8
	private static DelegateBridge __Hotfix0_HidePreview; // 0x10
	private static DelegateBridge __Hotfix0_GetPreviewInfo; // 0x18
	private static DelegateBridge __Hotfix0_IsInPreview; // 0x20
	private static DelegateBridge __Hotfix0_NeedHighLight; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 hidePreviewSeqNum { get; }

	// RVA: 0x2be9f30 VA: 0x7595201f30
	public Int32 get_hidePreviewSeqNum() { }
	// RVA: 0x2bea3f8 VA: 0x75952023f8
	public Void UpdatePreview(CrisisV2PreviewInfo info) { }
	// RVA: 0x2beab28 VA: 0x7595202b28
	public Int32 HidePreview() { }
	// RVA: 0x2bead88 VA: 0x7595202d88
	public CrisisV2PreviewInfo GetPreviewInfo() { }
	// RVA: 0x2beac6c VA: 0x7595202c6c
	public Boolean IsInPreview() { }
	// RVA: 0x2beaeb0 VA: 0x7595202eb0
	public Boolean NeedHighLight(String nodeOrBagId) { }
	// RVA: 0x2bf2dd8 VA: 0x759520add8
	public Void .ctor() { }
}
```