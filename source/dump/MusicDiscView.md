# MusicDiscView

**Namespace:** ` `


## Fields

- `RectTransform _transformDisc`

- `CanvasGroup _canvasDisc`

- `Image _imgDiscCover`

- `RectTransform _transformDiscCover`

- `Single _scaleDisc`

- `Single _transDuration`

- `Tween m_rotationSeq`

- `ArchiveMusicListDataBinder <closure>k__BackingField`


## Properties

- `ArchiveMusicListDataBinder closure`


## Methods

- `ArchiveMusicListDataBinder get_closure()`

- `Void set_closure(ArchiveMusicListDataBinder)`

- `Sprite _LoadDiscCoverSprite(MusicItemModel)`

- `Sequence GetAnimSequence(MusicItemModel)`

- `Void ToggleRotationAnim(Boolean)`

- `Void ResetPosition()`

- `Void Render(MusicItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MusicDiscView : IHotfixable
{
	private RectTransform _transformDisc; // 0x10
	private CanvasGroup _canvasDisc; // 0x18
	private Image _imgDiscCover; // 0x20
	private RectTransform _transformDiscCover; // 0x28
	private Single _scaleDisc; // 0x30
	private Single _transDuration; // 0x34
	private Tween m_rotationSeq; // 0x38
	private ArchiveMusicListDataBinder <closure>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_closure; // 0x0
	private static DelegateBridge __Hotfix0_set_closure; // 0x8
	private static DelegateBridge __Hotfix0__LoadDiscCoverSprite; // 0x10
	private static DelegateBridge __Hotfix0_GetAnimSequence; // 0x18
	private static DelegateBridge __Hotfix0_ToggleRotationAnim; // 0x20
	private static DelegateBridge __Hotfix0_ResetPosition; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ArchiveMusicListDataBinder closure { get; set; }

	// RVA: 0x3060a74 VA: 0x7595678a74
	private ArchiveMusicListDataBinder get_closure() { }
	// RVA: 0x305ed40 VA: 0x7595676d40
	public Void set_closure(ArchiveMusicListDataBinder value) { }
	// RVA: 0x3060adc VA: 0x7595678adc
	private Sprite _LoadDiscCoverSprite(MusicItemModel newModel) { }
	// RVA: 0x30602c4 VA: 0x75956782c4
	public Sequence GetAnimSequence(MusicItemModel newModel) { }
	// RVA: 0x305f9e8 VA: 0x75956779e8
	public Void ToggleRotationAnim(Boolean start) { }
	// RVA: 0x305eecc VA: 0x7595676ecc
	public Void ResetPosition() { }
	// RVA: 0x305f014 VA: 0x7595677014
	public Void Render(MusicItemModel newModel) { }
	// RVA: 0x3060c50 VA: 0x7595678c50
	public Void .ctor() { }
}
```