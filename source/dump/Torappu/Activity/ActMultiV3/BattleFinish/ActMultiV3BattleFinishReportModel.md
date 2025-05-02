# ActMultiV3BattleFinishReportModel

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `Int32 m_maxSelectCnt`

- `Boolean <isShow>k__BackingField`

- `Boolean <hasReproted>k__BackingField`

- `Boolean <isEmpty>k__BackingField`

- `String <reportTitle>k__BackingField`

- `String <nothingSelectToastDesc>k__BackingField`

- `Int32 <targetUserLv>k__BackingField`

- `String <targetUserName>k__BackingField`

- `String <targetUid>k__BackingField`

- `AvatarInfo <avatarInfo>k__BackingField`


## Properties

- `Boolean isShow`

- `Boolean hasReproted`

- `Boolean isEmpty`

- `String reportTitle`

- `String nothingSelectToastDesc`

- `Int32 targetUserLv`

- `String targetUserName`

- `String targetUid`

- `AvatarInfo avatarInfo`

- `Boolean isSelectMax`


## Methods

- `Boolean get_isShow()`

- `Void set_isShow(Boolean)`

- `Boolean get_hasReproted()`

- `Void set_hasReproted(Boolean)`

- `Boolean get_isEmpty()`

- `Void set_isEmpty(Boolean)`

- `String get_reportTitle()`

- `Void set_reportTitle(String)`

- `String get_nothingSelectToastDesc()`

- `Void set_nothingSelectToastDesc(String)`

- `Int32 get_targetUserLv()`

- `Void set_targetUserLv(Int32)`

- `String get_targetUserName()`

- `Void set_targetUserName(String)`

- `String get_targetUid()`

- `Void set_targetUid(String)`

- `AvatarInfo get_avatarInfo()`

- `Void set_avatarInfo(AvatarInfo)`

- `Boolean get_isSelectMax()`

- `Void LoadData(String, Boolean, MultiplayerInputPlayerInfo)`

- `Boolean CheckItemSelect(String)`

- `Void ToggleItemSelect(String)`

- `Void GenReportItemList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishReportModel : IHotfixable
{
	private List`1 m_itemList; // 0x10
	private HashSet`1 m_selectItemSet; // 0x18
	private Int32 m_maxSelectCnt; // 0x20
	private Boolean <isShow>k__BackingField; // 0x24
	private Boolean <hasReproted>k__BackingField; // 0x25
	private Boolean <isEmpty>k__BackingField; // 0x26
	private String <reportTitle>k__BackingField; // 0x28
	private String <nothingSelectToastDesc>k__BackingField; // 0x30
	private Int32 <targetUserLv>k__BackingField; // 0x38
	private String <targetUserName>k__BackingField; // 0x40
	private String <targetUid>k__BackingField; // 0x48
	private AvatarInfo <avatarInfo>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_set_isShow; // 0x8
	private static DelegateBridge __Hotfix0_get_hasReproted; // 0x10
	private static DelegateBridge __Hotfix0_set_hasReproted; // 0x18
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x20
	private static DelegateBridge __Hotfix0_set_isEmpty; // 0x28
	private static DelegateBridge __Hotfix0_get_reportTitle; // 0x30
	private static DelegateBridge __Hotfix0_set_reportTitle; // 0x38
	private static DelegateBridge __Hotfix0_get_nothingSelectToastDesc; // 0x40
	private static DelegateBridge __Hotfix0_set_nothingSelectToastDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_targetUserLv; // 0x50
	private static DelegateBridge __Hotfix0_set_targetUserLv; // 0x58
	private static DelegateBridge __Hotfix0_get_targetUserName; // 0x60
	private static DelegateBridge __Hotfix0_set_targetUserName; // 0x68
	private static DelegateBridge __Hotfix0_get_targetUid; // 0x70
	private static DelegateBridge __Hotfix0_set_targetUid; // 0x78
	private static DelegateBridge __Hotfix0_get_avatarInfo; // 0x80
	private static DelegateBridge __Hotfix0_set_avatarInfo; // 0x88
	private static DelegateBridge __Hotfix0_get_itemList; // 0x90
	private static DelegateBridge __Hotfix0_get_isSelectMax; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge __Hotfix0_CheckItemSelect; // 0xa8
	private static DelegateBridge __Hotfix0_ToggleItemSelect; // 0xb0
	private static DelegateBridge __Hotfix0_GenReportItemList; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Boolean isShow { get; set; }
	public Boolean hasReproted { get; set; }
	public Boolean isEmpty { get; set; }
	public String reportTitle { get; set; }
	public String nothingSelectToastDesc { get; set; }
	public Int32 targetUserLv { get; set; }
	public String targetUserName { get; set; }
	public String targetUid { get; set; }
	public AvatarInfo avatarInfo { get; set; }
	public List`1 itemList { get; }
	public Boolean isSelectMax { get; }

	// RVA: 0x3181e28 VA: 0x7595799e28
	public Boolean get_isShow() { }
	// RVA: 0x3181e90 VA: 0x7595799e90
	public Void set_isShow(Boolean value) { }
	// RVA: 0x317f590 VA: 0x7595797590
	public Boolean get_hasReproted() { }
	// RVA: 0x3181f10 VA: 0x7595799f10
	public Void set_hasReproted(Boolean value) { }
	// RVA: 0x317f528 VA: 0x7595797528
	public Boolean get_isEmpty() { }
	// RVA: 0x3181f90 VA: 0x7595799f90
	private Void set_isEmpty(Boolean value) { }
	// RVA: 0x3182010 VA: 0x759579a010
	public String get_reportTitle() { }
	// RVA: 0x3182078 VA: 0x759579a078
	private Void set_reportTitle(String value) { }
	// RVA: 0x31820fc VA: 0x759579a0fc
	public String get_nothingSelectToastDesc() { }
	// RVA: 0x3182164 VA: 0x759579a164
	private Void set_nothingSelectToastDesc(String value) { }
	// RVA: 0x31821e8 VA: 0x759579a1e8
	public Int32 get_targetUserLv() { }
	// RVA: 0x3182250 VA: 0x759579a250
	private Void set_targetUserLv(Int32 value) { }
	// RVA: 0x31822cc VA: 0x759579a2cc
	public String get_targetUserName() { }
	// RVA: 0x3182334 VA: 0x759579a334
	private Void set_targetUserName(String value) { }
	// RVA: 0x31823b8 VA: 0x759579a3b8
	public String get_targetUid() { }
	// RVA: 0x3182420 VA: 0x759579a420
	private Void set_targetUid(String value) { }
	// RVA: 0x31824a4 VA: 0x759579a4a4
	public AvatarInfo get_avatarInfo() { }
	// RVA: 0x318250c VA: 0x759579a50c
	private Void set_avatarInfo(AvatarInfo value) { }
	// RVA: 0x3182590 VA: 0x759579a590
	public List`1 get_itemList() { }
	// RVA: 0x31825f8 VA: 0x759579a5f8
	public Boolean get_isSelectMax() { }
	// RVA: 0x3182684 VA: 0x759579a684
	public Void LoadData(String actId, Boolean isTraining, MultiplayerInputPlayerInfo partnerPlayerInfo) { }
	// RVA: 0x3182b98 VA: 0x759579ab98
	public Boolean CheckItemSelect(String id) { }
	// RVA: 0x3182c38 VA: 0x759579ac38
	public Void ToggleItemSelect(String reportId) { }
	// RVA: 0x3182d54 VA: 0x759579ad54
	public Void GenReportItemList(List`1 reportItemList) { }
	// RVA: 0x3182f40 VA: 0x759579af40
	public Void .ctor() { }
}
```