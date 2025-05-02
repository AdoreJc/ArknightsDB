# SandboxV2SquadButtonView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _repoBtnGo`

- `GameObject _repoUnselectGo`

- `GameObject _repoSelectGo`

- `GameObject _squadTabGraphic`

- `SimpleLayoutContent _squadBtnList`

- `Boolean m_hasInited`

- `SquadBtnListAdapter m_squadListAdapter`


## Methods

- `Void set_onSquadTabClick(Action`1)`

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadButtonView : DataBinder`1
{
	private GameObject _repoBtnGo; // 0x20
	private GameObject _repoUnselectGo; // 0x28
	private GameObject _repoSelectGo; // 0x30
	private GameObject _squadTabGraphic; // 0x38
	private SimpleLayoutContent _squadBtnList; // 0x40
	private Boolean m_hasInited; // 0x48
	private SquadBtnListAdapter m_squadListAdapter; // 0x50
	private Action`1 <onSquadTabClick>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onSquadTabClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onSquadTabClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onSquadTabClick { get; set; }

	// RVA: 0x260e4c4 VA: 0x7594c264c4
	private Action`1 get_onSquadTabClick() { }
	// RVA: 0x260e52c VA: 0x7594c2652c
	public Void set_onSquadTabClick(Action`1 value) { }
	// RVA: 0x260e5b0 VA: 0x7594c265b0
	public override Void OnValueChanged(SandboxV2SquadGroupProp property) { }
	// RVA: 0x260e6cc VA: 0x7594c266cc
	private Void _InitIfNot() { }
	// RVA: 0x260e938 VA: 0x7594c26938
	private Void _RegisterTutorialGo() { }
	// RVA: 0x260ea24 VA: 0x7594c26a24
	public Void .ctor() { }
}
```