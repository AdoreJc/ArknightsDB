# EnemyDuelPrepareRoomViewModel

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String actId`

- `Param initBannerViewParam`

- `Single bannerRotateTime`

- `Int32 roomWaitPlayerTime`

- `EnemyDuelPrepareRoomStatusViewModel statusViewModel`

- `Int32 m_roomPlayerCntRequirement`

- `String m_checkingAvatarUID`

- `Int32 <checkingAvatarIdx>k__BackingField`


## Properties

- `Int32 checkingAvatarIdx`

- `Boolean addNpcFlag`

- `Int32 roomPlayerCntNeedToInvite`

- `Boolean isHostVision`


## Methods

- `Int32 get_checkingAvatarIdx()`

- `Void set_checkingAvatarIdx(Int32)`

- `Boolean get_addNpcFlag()`

- `Int32 get_roomPlayerCntNeedToInvite()`

- `Boolean get_isHostVision()`

- `Void _AfterTeamSvrUpdate()`

- `Void LoadData(String, Param)`

- `Void OnStatusUpdate()`

- `Void CheckAvatar(Int32)`

- `Void UncheckAvatar()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareRoomViewModel : IHotfixable
{
	public String actId; // 0x10
	public Param initBannerViewParam; // 0x18
	public Single bannerRotateTime; // 0x20
	public Int32 roomWaitPlayerTime; // 0x24
	public List`1 pingConds; // 0x28
	public EnemyDuelPrepareRoomStatusViewModel statusViewModel; // 0x30
	private Int32 m_roomPlayerCntRequirement; // 0x38
	private String m_checkingAvatarUID; // 0x40
	private Int32 <checkingAvatarIdx>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_checkingAvatarIdx; // 0x0
	private static DelegateBridge __Hotfix0_set_checkingAvatarIdx; // 0x8
	private static DelegateBridge __Hotfix0_get_addNpcFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_roomPlayerCntNeedToInvite; // 0x18
	private static DelegateBridge __Hotfix0_get_isHostVision; // 0x20
	private static DelegateBridge __Hotfix0__AfterTeamSvrUpdate; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_OnStatusUpdate; // 0x38
	private static DelegateBridge __Hotfix0_CheckAvatar; // 0x40
	private static DelegateBridge __Hotfix0_UncheckAvatar; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 checkingAvatarIdx { get; set; }
	public Boolean addNpcFlag { get; }
	public Int32 roomPlayerCntNeedToInvite { get; }
	public Boolean isHostVision { get; }

	// RVA: 0x29989e4 VA: 0x7594fb09e4
	public Int32 get_checkingAvatarIdx() { }
	// RVA: 0x299a488 VA: 0x7594fb2488
	private Void set_checkingAvatarIdx(Int32 value) { }
	// RVA: 0x299a258 VA: 0x7594fb2258
	public Boolean get_addNpcFlag() { }
	// RVA: 0x299a1d0 VA: 0x7594fb21d0
	public Int32 get_roomPlayerCntNeedToInvite() { }
	// RVA: 0x2998a4c VA: 0x7594fb0a4c
	public Boolean get_isHostVision() { }
	// RVA: 0x299a504 VA: 0x7594fb2504
	private Void _AfterTeamSvrUpdate() { }
	// RVA: 0x299a660 VA: 0x7594fb2660
	public Void LoadData(String actId, Param bannerParam) { }
	// RVA: 0x299a8a0 VA: 0x7594fb28a0
	public Void OnStatusUpdate() { }
	// RVA: 0x299acb8 VA: 0x7594fb2cb8
	public Void CheckAvatar(Int32 idx) { }
	// RVA: 0x299a5e4 VA: 0x7594fb25e4
	public Void UncheckAvatar() { }
	// RVA: 0x299adcc VA: 0x7594fb2dcc
	public Void .ctor() { }
}
```