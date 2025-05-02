# SideStoryViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Int64 m_createTs`

- `RetroActData <actInfo>k__BackingField`

- `RetroTrailData <trailData>k__BackingField`

- `Int32 totalStar`

- `Int32 maxStar`

- `Boolean <isStart>k__BackingField`

- `Boolean isTrailClear`

- `Boolean isTrailOnCountDown`

- `Boolean haveAvailReward`

- `Boolean isNewReward`

- `Boolean actOnShow`

- `String actId`

- `Boolean isFocus`

- `Boolean <isUnlock>k__BackingField`

- `Boolean hasChar`

- `Boolean isCharFullPotential`

- `PlayerCharacter relatedChar`


## Properties

- `RetroActData actInfo`

- `RetroTrailData trailData`

- `Boolean isStart`

- `Boolean isTrailShow`

- `Boolean isTrailCountDownFlag`

- `TimeSpan trailCountDownTime`

- `Boolean isUnlock`


## Methods

- `RetroActData get_actInfo()`

- `Void set_actInfo(RetroActData)`

- `RetroTrailData get_trailData()`

- `Void set_trailData(RetroTrailData)`

- `Boolean get_isStart()`

- `Void set_isStart(Boolean)`

- `Boolean get_isTrailShow()`

- `Boolean get_isTrailCountDownFlag()`

- `TimeSpan get_trailCountDownTime()`

- `Boolean get_isUnlock()`

- `Void set_isUnlock(Boolean)`

- `Void InitData(RetroActData, RetroTrailData, Int64)`

- `Void UpdatePlayerStatus()`

- `Void CheckAvailInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SideStoryViewModel : IHotfixable
{
	private Int64 m_createTs; // 0x10
	private RetroActData <actInfo>k__BackingField; // 0x18
	private RetroTrailData <trailData>k__BackingField; // 0x20
	public Int32 totalStar; // 0x28
	public Int32 maxStar; // 0x2c
	private Boolean <isStart>k__BackingField; // 0x30
	public Boolean isTrailClear; // 0x31
	public Boolean isTrailOnCountDown; // 0x32
	public Boolean haveAvailReward; // 0x33
	public Boolean isNewReward; // 0x34
	public Boolean actOnShow; // 0x35
	public String actId; // 0x38
	public Boolean isFocus; // 0x40
	private Boolean <isUnlock>k__BackingField; // 0x41
	public List`1 zoneList; // 0x48
	public List`1 trailViewModelList; // 0x50
	public Boolean hasChar; // 0x58
	public Boolean isCharFullPotential; // 0x59
	public PlayerCharacter relatedChar; // 0x60
	private static DelegateBridge __Hotfix0_get_actInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_actInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_trailData; // 0x10
	private static DelegateBridge __Hotfix0_set_trailData; // 0x18
	private static DelegateBridge __Hotfix0_get_isStart; // 0x20
	private static DelegateBridge __Hotfix0_set_isStart; // 0x28
	private static DelegateBridge __Hotfix0_get_isTrailShow; // 0x30
	private static DelegateBridge __Hotfix0_get_isTrailCountDownFlag; // 0x38
	private static DelegateBridge __Hotfix0_get_trailCountDownTime; // 0x40
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x48
	private static DelegateBridge __Hotfix0_set_isUnlock; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58
	private static DelegateBridge __Hotfix0_InitData; // 0x60
	private static DelegateBridge __Hotfix0_Create; // 0x68
	private static DelegateBridge __Hotfix0_get_customZoneClick; // 0x70
	private static DelegateBridge __Hotfix0_OnZoneClick; // 0x78
	private static DelegateBridge __Hotfix0_UpdatePlayerStatus; // 0x80
	private static DelegateBridge __Hotfix0_CheckAvailInfo; // 0x88

	public RetroActData actInfo { get; set; }
	public RetroTrailData trailData { get; set; }
	public Boolean isStart { get; set; }
	public Boolean isTrailShow { get; }
	public Boolean isTrailCountDownFlag { get; }
	public TimeSpan trailCountDownTime { get; }
	public Boolean isUnlock { get; set; }
	public virtual Boolean customZoneClick { get; }

	// RVA: 0x2f14e14 VA: 0x759552ce14
	public RetroActData get_actInfo() { }
	// RVA: 0x2f176ec VA: 0x759552f6ec
	private Void set_actInfo(RetroActData value) { }
	// RVA: 0x2f14dac VA: 0x759552cdac
	public RetroTrailData get_trailData() { }
	// RVA: 0x2f17770 VA: 0x759552f770
	private Void set_trailData(RetroTrailData value) { }
	// RVA: 0x2f177f4 VA: 0x759552f7f4
	public Boolean get_isStart() { }
	// RVA: 0x2f1785c VA: 0x759552f85c
	private Void set_isStart(Boolean value) { }
	// RVA: 0x2f178dc VA: 0x759552f8dc
	public Boolean get_isTrailShow() { }
	// RVA: 0x2f179e4 VA: 0x759552f9e4
	public Boolean get_isTrailCountDownFlag() { }
	// RVA: 0x2f17ab0 VA: 0x759552fab0
	public TimeSpan get_trailCountDownTime() { }
	// RVA: 0x2f1797c VA: 0x759552f97c
	public Boolean get_isUnlock() { }
	// RVA: 0x2f17b98 VA: 0x759552fb98
	private Void set_isUnlock(Boolean value) { }
	// RVA: 0x2f17c18 VA: 0x759552fc18
	protected Void .ctor() { }
	// RVA: 0x2f17d70 VA: 0x759552fd70
	private Void InitData(RetroActData actData, RetroTrailData trailData, Int64 curTs) { }
	// RVA: 0x2f17e20 VA: 0x759552fe20
	public static SideStoryViewModel Create(RetroActData actData, RetroTrailData trailData, Int64 curTs) { }
	// RVA: 0x2f18024 VA: 0x7595530024
	public virtual Boolean get_customZoneClick() { }
	// RVA: 0x2f18088 VA: 0x7595530088
	public virtual Void OnZoneClick(ZoneGroupViewModel zoneGroupModel, ZoneViewModel zoneModel) { }
	// RVA: 0x2f18108 VA: 0x7595530108
	public Void UpdatePlayerStatus() { }
	// RVA: 0x2f18224 VA: 0x7595530224
	public Void CheckAvailInfo() { }
}
```