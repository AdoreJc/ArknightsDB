# ArchiveMusicCardItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Text _title`

- `RectTransform _titleTransform`

- `Single _titleAnimDeltaY`

- `Text _count`

- `RectTransform _countTransform`

- `Single _countAnimDeltaY`

- `MusicItemModel m_cachedModel`


## Methods

- `Void Render(MusicItemModel)`

- `Void ResetPosition(Boolean)`

- `Sequence GetAnimSequence(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveMusicCardItemView : MonoBehaviour, IHotfixable
{
	private Text _title; // 0x18
	private RectTransform _titleTransform; // 0x20
	private Single _titleAnimDeltaY; // 0x28
	private Text _count; // 0x30
	private RectTransform _countTransform; // 0x38
	private Single _countAnimDeltaY; // 0x40
	private MusicItemModel m_cachedModel; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetPosition; // 0x8
	private static DelegateBridge __Hotfix0_GetAnimSequence; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x305d518 VA: 0x7595675518
	public Void Render(MusicItemModel model) { }
	// RVA: 0x305d66c VA: 0x759567566c
	public Void ResetPosition(Boolean isDown) { }
	// RVA: 0x305d7f8 VA: 0x75956757f8
	public Sequence GetAnimSequence(Boolean isShowing) { }
	// RVA: 0x305da14 VA: 0x7595675a14
	public Void .ctor() { }
}
```