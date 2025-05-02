# Act24sideMissionLoopAdapter

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `GameObject _missionObjPrefab`


## Methods

- `Void set_onClickCompleteBtn(Action`1)`

- `Void set_onClickDetailBtn(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionLoopAdapter : LoopScrollAdapter`2
{
	private GameObject _missionObjPrefab; // 0x58
	private Action`1 <onClickCompleteBtn>k__BackingField; // 0x60
	private Action`1 <onClickDetailBtn>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onClickCompleteBtn; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickCompleteBtn; // 0x8
	private static DelegateBridge __Hotfix0_get_onClickDetailBtn; // 0x10
	private static DelegateBridge __Hotfix0_set_onClickDetailBtn; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_CreateView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onClickCompleteBtn { get; set; }
	private Action`1 onClickDetailBtn { get; set; }

	// RVA: 0x32b7bf0 VA: 0x75958cfbf0
	private Action`1 get_onClickCompleteBtn() { }
	// RVA: 0x32b7c58 VA: 0x75958cfc58
	public Void set_onClickCompleteBtn(Action`1 value) { }
	// RVA: 0x32b7cdc VA: 0x75958cfcdc
	private Action`1 get_onClickDetailBtn() { }
	// RVA: 0x32b7d44 VA: 0x75958cfd44
	public Void set_onClickDetailBtn(Action`1 value) { }
	// RVA: 0x32b7dc8 VA: 0x75958cfdc8
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, Act24sideMissionObjViewModel data) { }
	// RVA: 0x32b8088 VA: 0x75958d0088
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x32b8148 VA: 0x75958d0148
	public Void .ctor() { }
}
```