# Act1VAutoChessHUDCampBuffOptionView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _buffNameText`

- `Text _buffDescText`

- `Text _buffTypeDescText`

- `Image _buffDecoImage`

- `UIAnimationLocation _selectAnimation`

- `ILoadAsset <iLoadAsset>k__BackingField`

- `Action <confirmSelectEvent>k__BackingField`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_selectTween`

- `Int32 m_index`

- `String m_decoIconId`


## Properties

- `ILoadAsset iLoadAsset`

- `Action confirmSelectEvent`


## Methods

- `ILoadAsset get_iLoadAsset()`

- `Void set_iLoadAsset(ILoadAsset)`

- `Void set_selectEvent(Action`1)`

- `Void set_confirmSelectEvent(Action)`

- `Action get_confirmSelectEvent()`

- `Void Render(Int32, Act1VAutoChessHUDCampBuffViewModel, Boolean, Boolean)`

- `Void _StartTutorialSignalCoroutine()`

- `IEnumerator _TryRaiseTutorialSignal()`

- `Void OnSelectEvent()`

- `Void OnConfirmSelectEvent()`

- `Void _InitIfNot()`

- `Boolean <_TryRaiseTutorialSignal>b__24_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampBuffOptionView : MonoBehaviour, IHotfixable
{
	private Text _buffNameText; // 0x18
	private Text _buffDescText; // 0x20
	private Text _buffTypeDescText; // 0x28
	private Image _buffDecoImage; // 0x30
	private UIAnimationLocation _selectAnimation; // 0x38
	private ILoadAsset <iLoadAsset>k__BackingField; // 0x48
	private Action`1 <selectEvent>k__BackingField; // 0x50
	private Action <confirmSelectEvent>k__BackingField; // 0x58
	private Boolean m_hasInited; // 0x60
	private UIPageFinder m_pageFinder; // 0x68
	private AnimationSwitchTween m_selectTween; // 0x78
	private Int32 m_index; // 0x80
	private String m_decoIconId; // 0x88
	private static DelegateBridge __Hotfix0_get_iLoadAsset; // 0x0
	private static DelegateBridge __Hotfix0_set_iLoadAsset; // 0x8
	private static DelegateBridge __Hotfix0_set_selectEvent; // 0x10
	private static DelegateBridge __Hotfix0_get_selectEvent; // 0x18
	private static DelegateBridge __Hotfix0_set_confirmSelectEvent; // 0x20
	private static DelegateBridge __Hotfix0_get_confirmSelectEvent; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0__StartTutorialSignalCoroutine; // 0x38
	private static DelegateBridge __Hotfix0__TryRaiseTutorialSignal; // 0x40
	private static DelegateBridge __Hotfix0_OnSelectEvent; // 0x48
	private static DelegateBridge __Hotfix0_OnConfirmSelectEvent; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private ILoadAsset iLoadAsset { get; set; }
	private Action`1 selectEvent { get; set; }
	private Action confirmSelectEvent { get; set; }

	// RVA: 0x3365854 VA: 0x759597d854
	private ILoadAsset get_iLoadAsset() { }
	// RVA: 0x33658bc VA: 0x759597d8bc
	public Void set_iLoadAsset(ILoadAsset value) { }
	// RVA: 0x3365940 VA: 0x759597d940
	public Void set_selectEvent(Action`1 value) { }
	// RVA: 0x33659c4 VA: 0x759597d9c4
	private Action`1 get_selectEvent() { }
	// RVA: 0x3365a2c VA: 0x759597da2c
	public Void set_confirmSelectEvent(Action value) { }
	// RVA: 0x3365ab0 VA: 0x759597dab0
	private Action get_confirmSelectEvent() { }
	// RVA: 0x3365b18 VA: 0x759597db18
	public Void Render(Int32 index, Act1VAutoChessHUDCampBuffViewModel model, Boolean isSelected, Boolean fastMode) { }
	// RVA: 0x3366028 VA: 0x759597e028
	private Void _StartTutorialSignalCoroutine() { }
	// RVA: 0x33660d0 VA: 0x759597e0d0
	private IEnumerator _TryRaiseTutorialSignal() { }
	// RVA: 0x33661a4 VA: 0x759597e1a4
	public Void OnSelectEvent() { }
	// RVA: 0x3366244 VA: 0x759597e244
	public Void OnConfirmSelectEvent() { }
	// RVA: 0x3365dac VA: 0x759597ddac
	private Void _InitIfNot() { }
	// RVA: 0x33662e0 VA: 0x759597e2e0
	public Void .ctor() { }
	// RVA: 0x3366350 VA: 0x759597e350
	private Boolean <_TryRaiseTutorialSignal>b__24_0() { }
}
```