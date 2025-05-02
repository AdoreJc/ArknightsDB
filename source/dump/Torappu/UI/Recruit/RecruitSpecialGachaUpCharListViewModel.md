# RecruitSpecialGachaUpCharListViewModel

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `String poolId`

- `String detailTitle`

- `String detailInfo`


## Properties

- `Boolean hasConfirmed`

- `Boolean isAllSelected`


## Methods

- `Boolean get_hasConfirmed()`

- `Boolean get_isAllSelected()`

- `Void RefreshData(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaUpCharListViewModel : IHotfixable
{
	public Dictionary`2 charGroupModel; // 0x10
	public String poolId; // 0x18
	public String detailTitle; // 0x20
	public String detailInfo; // 0x28
	public Dictionary`2 selectCharIdDict; // 0x30
	private static DelegateBridge __Hotfix0_get_hasConfirmed; // 0x0
	private static DelegateBridge __Hotfix0_get_isAllSelected; // 0x8
	private static DelegateBridge __Hotfix0_RefreshData; // 0x10
	private static DelegateBridge __Hotfix0_GenerateRarityCharDict; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean hasConfirmed { get; }
	public Boolean isAllSelected { get; }

	// RVA: 0x27030fc VA: 0x7594d1b0fc
	public Boolean get_hasConfirmed() { }
	// RVA: 0x2701148 VA: 0x7594d19148
	public Boolean get_isAllSelected() { }
	// RVA: 0x27028f0 VA: 0x7594d1a8f0
	public Void RefreshData(List`1 charIdList) { }
	// RVA: 0x2703244 VA: 0x7594d1b244
	public Dictionary`2 GenerateRarityCharDict() { }
	// RVA: 0x2703eac VA: 0x7594d1beac
	public Void .ctor() { }
}
```