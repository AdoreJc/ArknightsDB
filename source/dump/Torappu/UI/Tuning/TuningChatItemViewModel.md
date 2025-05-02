# TuningChatItemViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_actId`

- `String m_groupId`

- `String m_investId`

- `String m_investAvatarId`

- `Act29SideInvestType m_investType`

- `String m_investNpcName`

- `String m_storyId`

- `String m_npcPic`

- `Act29SideInvestResultData m_investSucResult`

- `Act29SideInvestResultData m_investFailResult`

- `Act29SideInvestResultData m_investRareResult`

- `Boolean m_hasRecv`

- `String m_fakeNpcAvatarId`


## Properties

- `String actId`

- `String investId`

- `String investAvatarId`

- `String groupId`

- `Act29SideInvestType investType`

- `String investNpcName`

- `String storyId`

- `String npcPic`

- `Act29SideInvestResultData investSucResult`

- `Act29SideInvestResultData investFailResult`

- `Act29SideInvestResultData investRareResult`

- `Boolean hasRecv`


## Methods

- `String get_actId()`

- `String get_investId()`

- `String get_investAvatarId()`

- `String get_groupId()`

- `Act29SideInvestType get_investType()`

- `String get_investNpcName()`

- `String get_storyId()`

- `String get_npcPic()`

- `Act29SideInvestResultData get_investSucResult()`

- `Act29SideInvestResultData get_investFailResult()`

- `Act29SideInvestResultData get_investRareResult()`

- `Boolean get_hasRecv()`

- `Void LoadData(String, Act29SideInvestData, Dictionary`2, Act29SideConstData, String)`

- `Void RefreshData(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatItemViewModel : IHotfixable
{
	private String m_actId; // 0x10
	private String m_groupId; // 0x18
	private String m_investId; // 0x20
	private String m_investAvatarId; // 0x28
	private Act29SideInvestType m_investType; // 0x30
	private String m_investNpcName; // 0x38
	private String m_storyId; // 0x40
	private String m_npcPic; // 0x48
	private Act29SideInvestResultData m_investSucResult; // 0x50
	private Act29SideInvestResultData m_investFailResult; // 0x58
	private Act29SideInvestResultData m_investRareResult; // 0x60
	private Boolean m_hasRecv; // 0x68
	private String m_fakeNpcAvatarId; // 0x70
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_investId; // 0x8
	private static DelegateBridge __Hotfix0_get_investAvatarId; // 0x10
	private static DelegateBridge __Hotfix0_get_groupId; // 0x18
	private static DelegateBridge __Hotfix0_get_investType; // 0x20
	private static DelegateBridge __Hotfix0_get_investNpcName; // 0x28
	private static DelegateBridge __Hotfix0_get_storyId; // 0x30
	private static DelegateBridge __Hotfix0_get_npcPic; // 0x38
	private static DelegateBridge __Hotfix0_get_investSucResult; // 0x40
	private static DelegateBridge __Hotfix0_get_investFailResult; // 0x48
	private static DelegateBridge __Hotfix0_get_investRareResult; // 0x50
	private static DelegateBridge __Hotfix0_get_hasRecv; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_RefreshData; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String actId { get; }
	public String investId { get; }
	public String investAvatarId { get; }
	public String groupId { get; }
	public Act29SideInvestType investType { get; }
	public String investNpcName { get; }
	public String storyId { get; }
	public String npcPic { get; }
	public Act29SideInvestResultData investSucResult { get; }
	public Act29SideInvestResultData investFailResult { get; }
	public Act29SideInvestResultData investRareResult { get; }
	public Boolean hasRecv { get; }

	// RVA: 0x231854c VA: 0x759493054c
	public String get_actId() { }
	// RVA: 0x2318360 VA: 0x7594930360
	public String get_investId() { }
	// RVA: 0x23186ec VA: 0x75949306ec
	public String get_investAvatarId() { }
	// RVA: 0x23185b4 VA: 0x75949305b4
	public String get_groupId() { }
	// RVA: 0x231861c VA: 0x759493061c
	public Act29SideInvestType get_investType() { }
	// RVA: 0x231cd48 VA: 0x7594934d48
	public String get_investNpcName() { }
	// RVA: 0x231cce0 VA: 0x7594934ce0
	public String get_storyId() { }
	// RVA: 0x231ec20 VA: 0x7594936c20
	public String get_npcPic() { }
	// RVA: 0x231ebb8 VA: 0x7594936bb8
	public Act29SideInvestResultData get_investSucResult() { }
	// RVA: 0x231f120 VA: 0x7594937120
	public Act29SideInvestResultData get_investFailResult() { }
	// RVA: 0x231f188 VA: 0x7594937188
	public Act29SideInvestResultData get_investRareResult() { }
	// RVA: 0x2318684 VA: 0x7594930684
	public Boolean get_hasRecv() { }
	// RVA: 0x23209e0 VA: 0x75949389e0
	public Void LoadData(String actId, Act29SideInvestData investData, Dictionary`2 resultDatas, Act29SideConstData constData, String slotId) { }
	// RVA: 0x231f098 VA: 0x7594937098
	public Void RefreshData(Boolean hasReceived) { }
	// RVA: 0x2320c50 VA: 0x7594938c50
	public Void .ctor() { }
}
```