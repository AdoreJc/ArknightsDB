# TimelinePicItemView

**Namespace:** ` `


## Fields

- `Image _imageThumbnail`

- `Image _imageFrame`

- `String m_cachedPicId`


## Properties

- `Image imageFrame`


## Methods

- `Image get_imageFrame()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TimelinePicItemView : TimelineResItemView`1
{
	private Image _imageThumbnail; // 0x68
	private Image _imageFrame; // 0x70
	private String m_cachedPicId; // 0x78
	private static DelegateBridge __Hotfix0_get_imageFrame; // 0x0
	private static DelegateBridge __Hotfix0__onSetController; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Image imageFrame { get; }

	// RVA: 0x3086d48 VA: 0x759569ed48
	protected Image get_imageFrame() { }
	// RVA: 0x3086db0 VA: 0x759569edb0
	protected override Void _onSetController(ArchiveTimelineController controller) { }
	// RVA: 0x308711c VA: 0x759569f11c
	public override Void ApplyData(TimelineResModel`1 model) { }
	// RVA: 0x308754c VA: 0x759569f54c
	public Void .ctor() { }
}
```