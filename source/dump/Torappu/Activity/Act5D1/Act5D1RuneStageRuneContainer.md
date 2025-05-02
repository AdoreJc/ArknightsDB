# Act5D1RuneStageRuneContainer

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `UIStringEvent _onClick`

- `SimpleLayoutContent _viewContainer`

- `TwoStateFadeSwitcher _allToggle`

- `TwoStateFadeSwitcher _dangerToggle`

- `TwoStateFadeSwitcher _newHandToggle`

- `Adapter m_adapter`

- `Boolean m_isInit`


## Methods

- `Void _InitIfNot()`

- `Void Render(List`1)`

- `Void SetAll()`

- `Void SetNewHand()`

- `Void SetDanger()`

- `Void SetType(RuneClassify)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneStageRuneContainer : MonoBehaviour, IHotfixable
{
	private UIStringEvent _onClick; // 0x18
	private SimpleLayoutContent _viewContainer; // 0x20
	private TwoStateFadeSwitcher _allToggle; // 0x28
	private TwoStateFadeSwitcher _dangerToggle; // 0x30
	private TwoStateFadeSwitcher _newHandToggle; // 0x38
	private Adapter m_adapter; // 0x40
	private Boolean m_isInit; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__GetDefaultClassRune; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_SetAll; // 0x18
	private static DelegateBridge __Hotfix0_SetNewHand; // 0x20
	private static DelegateBridge __Hotfix0_SetDanger; // 0x28
	private static DelegateBridge __Hotfix0_SetType; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x31cca84 VA: 0x75957e4a84
	private Void _InitIfNot() { }
	// RVA: 0x31ccbd4 VA: 0x75957e4bd4
	private static RuneClassify _GetDefaultClassRune() { }
	// RVA: 0x31ccd10 VA: 0x75957e4d10
	public Void Render(List`1 input) { }
	// RVA: 0x31ccdcc VA: 0x75957e4dcc
	public Void SetAll() { }
	// RVA: 0x31cce38 VA: 0x75957e4e38
	public Void SetNewHand() { }
	// RVA: 0x31ccea4 VA: 0x75957e4ea4
	public Void SetDanger() { }
	// RVA: 0x31ccc30 VA: 0x75957e4c30
	public Void SetType(RuneClassify classify) { }
	// RVA: 0x31ccf10 VA: 0x75957e4f10
	public Void .ctor() { }
}
```