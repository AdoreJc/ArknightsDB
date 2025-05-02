# UniEquipArchiveFilterView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `TwoStateToggle _trackToggle`

- `GameObject _panelTrack`

- `Text _trackNum1`

- `Text _trackNum2`

- `RectTransform _cursorRect`

- `RectTransform _cursorContainer`

- `Boolean m_isInited`

- `Int32 m_fastSeq`

- `Tween m_moveTween`

- `RectTransform m_cachedCursorTarget`


## Methods

- `Void _InitIfNot()`

- `Void _MoveCursor(RectTransform, Boolean)`

- `Void _OnToggle(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveFilterView : DataBinder`1
{
	private const Single MOVE_DURATION; // 0x0
	private List`1 _equipItems; // 0x20
	private TwoStateToggle _trackToggle; // 0x28
	private GameObject _panelTrack; // 0x30
	private Text _trackNum1; // 0x38
	private Text _trackNum2; // 0x40
	private RectTransform _cursorRect; // 0x48
	private RectTransform _cursorContainer; // 0x50
	public Action`1 onShowTrackClick; // 0x58
	public Action`1 onUnlockTabClick; // 0x60
	private Boolean m_isInited; // 0x68
	private Int32 m_fastSeq; // 0x6c
	private Tween m_moveTween; // 0x70
	private RectTransform m_cachedCursorTarget; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__MoveCursor; // 0x10
	private static DelegateBridge __Hotfix0__OnToggle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x22e4e6c VA: 0x75948fce6c
	private Void _InitIfNot() { }
	// RVA: 0x22e502c VA: 0x75948fd02c
	public override Void OnValueChanged(UniEquipArchiveFilterProperty property) { }
	// RVA: 0x22e52ac VA: 0x75948fd2ac
	private Void _MoveCursor(RectTransform target, Boolean isFastMode) { }
	// RVA: 0x22e54cc VA: 0x75948fd4cc
	private Void _OnToggle(State state) { }
	// RVA: 0x22e5570 VA: 0x75948fd570
	public Void .ctor() { }
}
```