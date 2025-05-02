# RecruitSpecialGachaItemView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RecruitSpecialGachaInitView _initView`

- `RecruitSpecialGachaNormalView _normalView`

- `RecruitSpecialGachaProperty m_property`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_dialogInstId`


## Methods

- `Void ApplyData(Int32, GachaPoolClientData)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _EventOnSelectCharBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaItemView : RecruitGachaItemViewBase, ICompDialogCallBack, IHotfixable
{
	private RecruitSpecialGachaInitView _initView; // 0x60
	private RecruitSpecialGachaNormalView _normalView; // 0x68
	private RecruitSpecialGachaProperty m_property; // 0x70
	private Boolean m_hasInited; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private Int32 m_dialogInstId; // 0x90
	private static DelegateBridge __Hotfix0_get_gachaPoolId; // 0x0
	private static DelegateBridge __Hotfix0_OnRefreshData; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x18
	private static DelegateBridge __Hotfix0__EventOnSelectCharBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override String gachaPoolId { get; }

	// RVA: 0x271cde4 VA: 0x7594d34de4
	public override String get_gachaPoolId() { }
	// RVA: 0x271ce90 VA: 0x7594d34e90
	protected override Void OnRefreshData() { }
	// RVA: 0x271d4fc VA: 0x7594d354fc
	public Void ApplyData(Int32 index, GachaPoolClientData data) { }
	// RVA: 0x271d840 VA: 0x7594d35840
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x271d92c VA: 0x7594d3592c
	private Void _EventOnSelectCharBtnClicked() { }
	// RVA: 0x271cf4c VA: 0x7594d34f4c
	private Void _InitIfNot() { }
	// RVA: 0x271dd04 VA: 0x7594d35d04
	public Void .ctor() { }
}
```