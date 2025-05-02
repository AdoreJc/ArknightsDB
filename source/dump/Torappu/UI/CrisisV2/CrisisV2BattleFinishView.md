# CrisisV2BattleFinishView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2SettleView _viewPrefab`

- `RectTransform _container`

- `CrisisV2SettleView m_settleView`

- `CrisisV2CacheServerData m_crisisV2ServerData`


## Methods

- `Void _OnClose()`

- `Boolean _LoadResponseData(Param, out)`

- `Boolean _LoadMapData(Param, String)`

- `Boolean _LoadSquadData(Param)`

- `Void _AddDataToTempCommentList(List`1, Boolean, Dictionary`2, ref)`

- `Boolean _LoadCommentsByResponse(CrisisV2BattleFinishResponse, String, ref)`

- `Boolean _LoadRuneDataByResponse(CrisisV2BattleFinishResponse, String, ref)`

- `Void <OnInit>b__4_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2BattleFinishView : DynBattleFinishView, IHotfixable
{
	private CrisisV2SettleView _viewPrefab; // 0x20
	private RectTransform _container; // 0x28
	private CrisisV2SettleView m_settleView; // 0x30
	private CrisisV2CacheServerData m_crisisV2ServerData; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__OnClose; // 0x8
	private static DelegateBridge __Hotfix0__LoadResponseData; // 0x10
	private static DelegateBridge __Hotfix0__LoadMapData; // 0x18
	private static DelegateBridge __Hotfix0__LoadSquadData; // 0x20
	private static DelegateBridge __Hotfix0__GetCommentDict; // 0x28
	private static DelegateBridge __Hotfix0__AddDataToTempCommentList; // 0x30
	private static DelegateBridge __Hotfix0__LoadCommentsByResponse; // 0x38
	private static DelegateBridge __Hotfix0__LoadRuneDataByResponse; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2bc3f24 VA: 0x75951dbf24
	protected override Void OnInit() { }
	// RVA: 0x2bc4a94 VA: 0x75951dca94
	private Void _OnClose() { }
	// RVA: 0x2bc427c VA: 0x75951dc27c
	private Boolean _LoadResponseData(Param input, out String mapId) { }
	// RVA: 0x2bc44f4 VA: 0x75951dc4f4
	private Boolean _LoadMapData(Param input, String mapId) { }
	// RVA: 0x2bc47dc VA: 0x75951dc7dc
	private Boolean _LoadSquadData(Param input) { }
	// RVA: 0x2bc5124 VA: 0x75951dd124
	private Dictionary`2 _GetCommentDict(String _mapId) { }
	// RVA: 0x2bc51fc VA: 0x75951dd1fc
	private Void _AddDataToTempCommentList(List`1 commentIdList, Boolean isNewList, Dictionary`2 commentDic, ref List`1 tempCommentList) { }
	// RVA: 0x2bc4af8 VA: 0x75951dcaf8
	private Boolean _LoadCommentsByResponse(CrisisV2BattleFinishResponse response, String mapId, ref List`1 commentList) { }
	// RVA: 0x2bc4d40 VA: 0x75951dcd40
	private Boolean _LoadRuneDataByResponse(CrisisV2BattleFinishResponse response, String mapId, ref List`1 runeList) { }
	// RVA: 0x2bc546c VA: 0x75951dd46c
	public Void .ctor() { }
	// RVA: 0x2bc54dc VA: 0x75951dd4dc
	private Void <OnInit>b__4_0() { }
}
```