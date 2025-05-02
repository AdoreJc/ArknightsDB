# Act42D0EntryNormalMapBtnViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String <latestAreaCode>k__BackingField`

- `String <latestStageCode>k__BackingField`

- `String <ratingIconId>k__BackingField`

- `Boolean <allClear>k__BackingField`

- `Boolean <isTimeOut>k__BackingField`

- `String m_latestAreaId`

- `Int32 m_latestStageRating`


## Properties

- `String latestAreaCode`

- `String latestStageCode`

- `String ratingIconId`

- `Boolean allClear`

- `Boolean isTimeOut`


## Methods

- `String get_latestAreaCode()`

- `Void set_latestAreaCode(String)`

- `String get_latestStageCode()`

- `Void set_latestStageCode(String)`

- `String get_ratingIconId()`

- `Void set_ratingIconId(String)`

- `Boolean get_allClear()`

- `Void set_allClear(Boolean)`

- `Boolean get_isTimeOut()`

- `Void set_isTimeOut(Boolean)`

- `Void LoadData(ActivityBasicInfo)`

- `Void _SetDataDefaultEmpty()`

- `String _GetAreaCodeById(Act42D0Data, String)`

- `Int32 _GetStageRatingById(PlayerAct42D0Activity, String, String)`

- `String _GetRatingIconId(Act42D0Data, String, Int32)`

- `Boolean _CheckIfFinalStage(Act42D0Data, String, String)`

- `Boolean _CheckIfCompleted(Act42D0Data, String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EntryNormalMapBtnViewModel : TemplateActivityViewModel
{
	private String <latestAreaCode>k__BackingField; // 0x20
	private String <latestStageCode>k__BackingField; // 0x28
	private String <ratingIconId>k__BackingField; // 0x30
	private Boolean <allClear>k__BackingField; // 0x38
	private Boolean <isTimeOut>k__BackingField; // 0x39
	private String m_latestAreaId; // 0x40
	private Int32 m_latestStageRating; // 0x48
	private static DelegateBridge __Hotfix0_get_latestAreaCode; // 0x0
	private static DelegateBridge __Hotfix0_set_latestAreaCode; // 0x8
	private static DelegateBridge __Hotfix0_get_latestStageCode; // 0x10
	private static DelegateBridge __Hotfix0_set_latestStageCode; // 0x18
	private static DelegateBridge __Hotfix0_get_ratingIconId; // 0x20
	private static DelegateBridge __Hotfix0_set_ratingIconId; // 0x28
	private static DelegateBridge __Hotfix0_get_allClear; // 0x30
	private static DelegateBridge __Hotfix0_set_allClear; // 0x38
	private static DelegateBridge __Hotfix0_get_isTimeOut; // 0x40
	private static DelegateBridge __Hotfix0_set_isTimeOut; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0__SetDataDefaultEmpty; // 0x60
	private static DelegateBridge __Hotfix0__GetAreaCodeById; // 0x68
	private static DelegateBridge __Hotfix0__GetStageRatingById; // 0x70
	private static DelegateBridge __Hotfix0__GetRatingIconId; // 0x78
	private static DelegateBridge __Hotfix0__CheckIfFinalStage; // 0x80
	private static DelegateBridge __Hotfix0__CheckIfCompleted; // 0x88

	public String latestAreaCode { get; set; }
	public String latestStageCode { get; set; }
	public String ratingIconId { get; set; }
	public Boolean allClear { get; set; }
	public Boolean isTimeOut { get; set; }

	// RVA: 0x3215c60 VA: 0x759582dc60
	public String get_latestAreaCode() { }
	// RVA: 0x3215cc8 VA: 0x759582dcc8
	private Void set_latestAreaCode(String value) { }
	// RVA: 0x3215d4c VA: 0x759582dd4c
	public String get_latestStageCode() { }
	// RVA: 0x3215db4 VA: 0x759582ddb4
	private Void set_latestStageCode(String value) { }
	// RVA: 0x3215e38 VA: 0x759582de38
	public String get_ratingIconId() { }
	// RVA: 0x3215ea0 VA: 0x759582dea0
	private Void set_ratingIconId(String value) { }
	// RVA: 0x3215f24 VA: 0x759582df24
	public Boolean get_allClear() { }
	// RVA: 0x3215f8c VA: 0x759582df8c
	private Void set_allClear(Boolean value) { }
	// RVA: 0x321600c VA: 0x759582e00c
	public Boolean get_isTimeOut() { }
	// RVA: 0x3216074 VA: 0x759582e074
	private Void set_isTimeOut(Boolean value) { }
	// RVA: 0x32160f4 VA: 0x759582e0f4
	public Void .ctor(Object param) { }
	// RVA: 0x32161dc VA: 0x759582e1dc
	public Void LoadData(ActivityBasicInfo basicInfo) { }
	// RVA: 0x3216450 VA: 0x759582e450
	private Void _SetDataDefaultEmpty() { }
	// RVA: 0x3216518 VA: 0x759582e518
	private String _GetAreaCodeById(Act42D0Data data, String areaId) { }
	// RVA: 0x3216604 VA: 0x759582e604
	private Int32 _GetStageRatingById(PlayerAct42D0Activity playerData, String areaId, String stageId) { }
	// RVA: 0x3216798 VA: 0x759582e798
	private String _GetRatingIconId(Act42D0Data data, String stageId, Int32 rating) { }
	// RVA: 0x3216978 VA: 0x759582e978
	private Boolean _CheckIfFinalStage(Act42D0Data data, String areaId, String stageId) { }
	// RVA: 0x3216d88 VA: 0x759582ed88
	private Boolean _CheckIfCompleted(Act42D0Data data, String stageId, Int32 ratingGot) { }
}
```