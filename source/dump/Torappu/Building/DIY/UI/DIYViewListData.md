# DIYViewListData

**Namespace:** `Torappu.Building.DIY.UI`


## Methods

- `Boolean IsEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYViewListData : IHotfixable
{
	private List`1 m_viewlistDatas; // 0x10
	private static DelegateBridge __Hotfix0_get_viewlistDatas; // 0x0
	private static DelegateBridge __Hotfix0_get_viewlistGroupDatas; // 0x8
	private static DelegateBridge __Hotfix0_get_funcGroupDatas; // 0x10
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x18
	private static DelegateBridge __Hotfix0_op_Implicit; // 0x20
	private static DelegateBridge __Hotfix0_AddDataToGroupDict; // 0x28
	private static DelegateBridge __Hotfix0__GetGroupDataFromDatas; // 0x30
	private static DelegateBridge __Hotfix0__GetFuncDataFromDatas; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 viewlistDatas { get; }
	public Dictionary`2 viewlistGroupDatas { get; }
	public Dictionary`2 funcGroupDatas { get; }

	// RVA: 0x38415c4 VA: 0x7595e595c4
	public List`1 get_viewlistDatas() { }
	// RVA: 0x384162c VA: 0x7595e5962c
	public Dictionary`2 get_viewlistGroupDatas() { }
	// RVA: 0x3841b04 VA: 0x7595e59b04
	public Dictionary`2 get_funcGroupDatas() { }
	// RVA: 0x3842044 VA: 0x7595e5a044
	public Boolean IsEmpty() { }
	// RVA: 0x38420d0 VA: 0x7595e5a0d0
	public static DIYViewListData op_Implicit(List`1 listDatas) { }
	// RVA: 0x38421d0 VA: 0x7595e5a1d0
	public Dictionary`2 AddDataToGroupDict(Dictionary`2 groupDatas) { }
	// RVA: 0x3841694 VA: 0x7595e59694
	private Dictionary`2 _GetGroupDataFromDatas() { }
	// RVA: 0x3841b70 VA: 0x7595e59b70
	private Dictionary`2 _GetFuncDataFromDatas(List`1 listDatas) { }
	// RVA: 0x3842160 VA: 0x7595e5a160
	public Void .ctor() { }
}
```