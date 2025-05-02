# Act1VAutoChessEquipReplaceItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _equipIconImage`

- `Text _equipNameText`

- `Text _equipDescText`

- `CanvasGroup _selectGroup`

- `Single _fadeDuration`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `FadeSwitchTween m_selectTween`

- `Int32 m_index`

- `String m_equipIconId`


## Methods

- `Void set_selectEvent(Action`1)`

- `Void set_confirmEvent(Action`1)`

- `Void Render(Int32, Act1VAutoChessEquipReplaceItemViewModel, Boolean, Boolean)`

- `Void OnSelectEvent()`

- `Void OnConfirmEvent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEquipReplaceItemView : MonoBehaviour, IHotfixable
{
	private Image _equipIconImage; // 0x18
	private Text _equipNameText; // 0x20
	private Text _equipDescText; // 0x28
	private CanvasGroup _selectGroup; // 0x30
	private Single _fadeDuration; // 0x38
	private Boolean m_hasInited; // 0x3c
	private ILoadAsset m_iLoadAsset; // 0x40
	private FadeSwitchTween m_selectTween; // 0x48
	private Int32 m_index; // 0x50
	private String m_equipIconId; // 0x58
	private Action`1 <selectEvent>k__BackingField; // 0x60
	private Action`1 <confirmEvent>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_selectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_selectEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_confirmEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_confirmEvent; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnSelectEvent; // 0x28
	private static DelegateBridge __Hotfix0_OnConfirmEvent; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action`1 selectEvent { get; set; }
	private Action`1 confirmEvent { get; set; }

	// RVA: 0x336e7e8 VA: 0x75959867e8
	private Action`1 get_selectEvent() { }
	// RVA: 0x336e850 VA: 0x7595986850
	public Void set_selectEvent(Action`1 value) { }
	// RVA: 0x336e8d4 VA: 0x75959868d4
	private Action`1 get_confirmEvent() { }
	// RVA: 0x336e93c VA: 0x759598693c
	public Void set_confirmEvent(Action`1 value) { }
	// RVA: 0x336e9c0 VA: 0x75959869c0
	public Void Render(Int32 index, Act1VAutoChessEquipReplaceItemViewModel model, Boolean selected, Boolean fastMode) { }
	// RVA: 0x336eca0 VA: 0x7595986ca0
	public Void OnSelectEvent() { }
	// RVA: 0x336ed40 VA: 0x7595986d40
	public Void OnConfirmEvent() { }
	// RVA: 0x336eb8c VA: 0x7595986b8c
	private Void _InitIfNot() { }
	// RVA: 0x336ede0 VA: 0x7595986de0
	public Void .ctor() { }
}
```