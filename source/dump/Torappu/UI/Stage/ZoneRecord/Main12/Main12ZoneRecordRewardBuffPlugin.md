# Main12ZoneRecordRewardBuffPlugin

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `GameObject m_itemTimeObj`

- `Main12RecordRewardBuffBtnView m_view`

- `Int64 m_rewardBuffTimeEndTs`

- `Int64 m_rewardBuffTimeStartTs`

- `String m_itemId`

- `Boolean isOnStage`


## Methods

- `Void _OnTimeOut()`

- `Void <>xLuaBaseProxy_OnRender(ZoneRewardBuffViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12ZoneRecordRewardBuffPlugin : ZoneRecordRewardBuffPlugin
{
	private GameObject m_itemTimeObj; // 0x28
	private Main12RecordRewardBuffBtnView m_view; // 0x30
	private Int64 m_rewardBuffTimeEndTs; // 0x38
	private Int64 m_rewardBuffTimeStartTs; // 0x40
	private String m_itemId; // 0x48
	public Boolean isOnStage; // 0x50
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__OnTimeOut; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2fd4b14 VA: 0x75955ecb14
	public override Void OnRender(ZoneRewardBuffViewModel viewModel) { }
	// RVA: 0x2fd4db8 VA: 0x75955ecdb8
	private Void _OnTimeOut() { }
	// RVA: 0x2fd4e38 VA: 0x75955ece38
	public Void .ctor() { }
	// RVA: 0x2fd4ea4 VA: 0x75955ecea4
	private Void <>xLuaBaseProxy_OnRender(ZoneRewardBuffViewModel P0) { }
}
```