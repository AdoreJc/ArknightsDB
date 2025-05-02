# TimelineClip

**Namespace:** `UnityEngine.Timeline`


## Fields

- `Int32 m_Version`

- `Double m_Start`

- `Double m_ClipIn`

- `Object m_Asset`

- `Double m_Duration`

- `Double m_TimeScale`

- `TrackAsset m_ParentTrack`

- `Double m_EaseInDuration`

- `Double m_EaseOutDuration`

- `Double m_BlendInDuration`

- `Double m_BlendOutDuration`

- `AnimationCurve m_MixInCurve`

- `AnimationCurve m_MixOutCurve`

- `BlendCurveMode m_BlendInCurveMode`

- `BlendCurveMode m_BlendOutCurveMode`

- `AnimationClip m_AnimationCurves`

- `Boolean m_Recordable`

- `ClipExtrapolation m_PostExtrapolationMode`

- `ClipExtrapolation m_PreExtrapolationMode`

- `Double m_PostExtrapolationTime`

- `Double m_PreExtrapolationTime`

- `String m_DisplayName`


## Properties

- `Double timeScale`

- `Double start`

- `Double duration`

- `Double end`

- `Double clipIn`

- `String displayName`

- `AnimationClip curves`

- `Object asset`

- `Double easeInDuration`

- `Double easeOutDuration`

- `Double blendInDuration`

- `Double blendOutDuration`

- `Boolean hasBlendIn`

- `Boolean hasBlendOut`

- `AnimationCurve mixInCurve`

- `Double mixInDuration`

- `AnimationCurve mixOutCurve`

- `Double mixOutTime`

- `Double mixOutDuration`

- `Boolean recordable`

- `ClipCaps clipCaps`

- `ClipExtrapolation postExtrapolationMode`

- `ClipExtrapolation preExtrapolationMode`

- `Double extrapolatedStart`

- `Double extrapolatedDuration`


## Methods

- `Void UpgradeToLatestVersion()`

- `Double get_timeScale()`

- `Double get_start()`

- `Void set_start(Double)`

- `Double get_duration()`

- `Void set_duration(Double)`

- `Double get_end()`

- `Double get_clipIn()`

- `String get_displayName()`

- `Void set_displayName(String)`

- `AnimationClip get_curves()`

- `Object get_asset()`

- `Void set_asset(Object)`

- `TrackAsset GetParentTrack()`

- `Double get_easeInDuration()`

- `Double get_easeOutDuration()`

- `Double get_blendInDuration()`

- `Double get_blendOutDuration()`

- `Boolean get_hasBlendIn()`

- `Boolean get_hasBlendOut()`

- `AnimationCurve get_mixInCurve()`

- `Void set_mixInCurve(AnimationCurve)`

- `Double get_mixInDuration()`

- `AnimationCurve get_mixOutCurve()`

- `Void set_mixOutCurve(AnimationCurve)`

- `Double get_mixOutTime()`

- `Double get_mixOutDuration()`

- `Boolean get_recordable()`

- `ClipCaps get_clipCaps()`

- `Single EvaluateMixOut(Double)`

- `Single EvaluateMixIn(Double)`

- `Double ToLocalTime(Double)`

- `ClipExtrapolation get_postExtrapolationMode()`

- `ClipExtrapolation get_preExtrapolationMode()`

- `Boolean IsPreExtrapolatedTime(Double)`

- `Boolean IsPostExtrapolatedTime(Double)`

- `Double get_extrapolatedStart()`

- `Double get_extrapolatedDuration()`

- `Void UpdateDirty(Double, Double)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
public class TimelineClip : ICurvesOwner, ISerializationCallbackReceiver
{
	private const Int32 k_LatestVersion; // 0x0
	private Int32 m_Version; // 0x10
	public static readonly ClipCaps kDefaultClipCaps; // 0x0
	public static readonly Single kDefaultClipDurationInSeconds; // 0x4
	public static readonly Double kTimeScaleMin; // 0x8
	public static readonly Double kTimeScaleMax; // 0x10
	internal static readonly String kDefaultCurvesName; // 0x18
	internal static readonly Double kMinDuration; // 0x20
	internal static readonly Double kMaxTimeValue; // 0x28
	private Double m_Start; // 0x18
	private Double m_ClipIn; // 0x20
	private Object m_Asset; // 0x28
	private Double m_Duration; // 0x30
	private Double m_TimeScale; // 0x38
	private TrackAsset m_ParentTrack; // 0x40
	private Double m_EaseInDuration; // 0x48
	private Double m_EaseOutDuration; // 0x50
	private Double m_BlendInDuration; // 0x58
	private Double m_BlendOutDuration; // 0x60
	private AnimationCurve m_MixInCurve; // 0x68
	private AnimationCurve m_MixOutCurve; // 0x70
	private BlendCurveMode m_BlendInCurveMode; // 0x78
	private BlendCurveMode m_BlendOutCurveMode; // 0x7c
	private List`1 m_ExposedParameterNames; // 0x80
	private AnimationClip m_AnimationCurves; // 0x88
	private Boolean m_Recordable; // 0x90
	private ClipExtrapolation m_PostExtrapolationMode; // 0x94
	private ClipExtrapolation m_PreExtrapolationMode; // 0x98
	private Double m_PostExtrapolationTime; // 0xa0
	private Double m_PreExtrapolationTime; // 0xa8
	private String m_DisplayName; // 0xb0

	public Double timeScale { get; }
	public Double start { get; set; }
	public Double duration { get; set; }
	public Double end { get; }
	public Double clipIn { get; }
	public String displayName { get; set; }
	public AnimationClip curves { get; }
	private String UnityEngine.Timeline.ICurvesOwner.defaultCurvesName { get; }
	public Object asset { get; set; }
	private Object UnityEngine.Timeline.ICurvesOwner.assetOwner { get; }
	private TrackAsset UnityEngine.Timeline.ICurvesOwner.targetTrack { get; }
	public Double easeInDuration { get; }
	public Double easeOutDuration { get; }
	public Double blendInDuration { get; }
	public Double blendOutDuration { get; }
	public Boolean hasBlendIn { get; }
	public Boolean hasBlendOut { get; }
	public AnimationCurve mixInCurve { get; set; }
	public Double mixInDuration { get; }
	public AnimationCurve mixOutCurve { get; set; }
	public Double mixOutTime { get; }
	public Double mixOutDuration { get; }
	public Boolean recordable { get; set; }
	public ClipCaps clipCaps { get; }
	public ClipExtrapolation postExtrapolationMode { get; set; }
	public ClipExtrapolation preExtrapolationMode { get; set; }
	public Double extrapolatedStart { get; }
	public Double extrapolatedDuration { get; }

	// RVA: 0x6821764 VA: 0x7598e39764
	private Void UpgradeToLatestVersion() { }
	// RVA: 0x68217d8 VA: 0x7598e397d8
	internal Void .ctor(TrackAsset parent) { }
	// RVA: 0x682191c VA: 0x7598e3991c
	public Double get_timeScale() { }
	// RVA: 0x6821ae4 VA: 0x7598e39ae4
	public Double get_start() { }
	// RVA: 0x681db34 VA: 0x7598e35b34
	public Void set_start(Double value) { }
	// RVA: 0x6821c90 VA: 0x7598e39c90
	public Double get_duration() { }
	// RVA: 0x681dc38 VA: 0x7598e35c38
	public Void set_duration(Double value) { }
	// RVA: 0x6821c98 VA: 0x7598e39c98
	public Double get_end() { }
	// RVA: 0x6821ca8 VA: 0x7598e39ca8
	public Double get_clipIn() { }
	// RVA: 0x6821cc8 VA: 0x7598e39cc8
	public String get_displayName() { }
	// RVA: 0x6821cd0 VA: 0x7598e39cd0
	public Void set_displayName(String value) { }
	// RVA: 0x6821cd8 VA: 0x7598e39cd8
	public AnimationClip get_curves() { }
	// RVA: 0x6821ce0 VA: 0x7598e39ce0
	private String UnityEngine.Timeline.ICurvesOwner.get_defaultCurvesName() { }
	// RVA: 0x6821d38 VA: 0x7598e39d38
	public Object get_asset() { }
	// RVA: 0x6821d40 VA: 0x7598e39d40
	public Void set_asset(Object value) { }
	// RVA: 0x6821d48 VA: 0x7598e39d48
	private Object UnityEngine.Timeline.ICurvesOwner.get_assetOwner() { }
	// RVA: 0x6821d50 VA: 0x7598e39d50
	private TrackAsset UnityEngine.Timeline.ICurvesOwner.get_targetTrack() { }
	// RVA: 0x6821d58 VA: 0x7598e39d58
	public TrackAsset GetParentTrack() { }
	// RVA: 0x6821814 VA: 0x7598e39814
	internal Void SetParentTrack_Internal(TrackAsset newParentTrack) { }
	// RVA: 0x6821ebc VA: 0x7598e39ebc
	public Double get_easeInDuration() { }
	// RVA: 0x6821fa4 VA: 0x7598e39fa4
	public Double get_easeOutDuration() { }
	// RVA: 0x682208c VA: 0x7598e3a08c
	public Double get_blendInDuration() { }
	// RVA: 0x68220ac VA: 0x7598e3a0ac
	public Double get_blendOutDuration() { }
	// RVA: 0x6822060 VA: 0x7598e3a060
	public Boolean get_hasBlendIn() { }
	// RVA: 0x6821f78 VA: 0x7598e39f78
	public Boolean get_hasBlendOut() { }
	// RVA: 0x68220cc VA: 0x7598e3a0cc
	public AnimationCurve get_mixInCurve() { }
	// RVA: 0x6822178 VA: 0x7598e3a178
	public Void set_mixInCurve(AnimationCurve value) { }
	// RVA: 0x6822180 VA: 0x7598e3a180
	public Double get_mixInDuration() { }
	// RVA: 0x68221c4 VA: 0x7598e3a1c4
	public AnimationCurve get_mixOutCurve() { }
	// RVA: 0x6822270 VA: 0x7598e3a270
	public Void set_mixOutCurve(AnimationCurve value) { }
	// RVA: 0x6822278 VA: 0x7598e3a278
	public Double get_mixOutTime() { }
	// RVA: 0x68222a4 VA: 0x7598e3a2a4
	public Double get_mixOutDuration() { }
	// RVA: 0x68222e8 VA: 0x7598e3a2e8
	public Boolean get_recordable() { }
	// RVA: 0x68222f0 VA: 0x7598e3a2f0
	internal Void set_recordable(Boolean value) { }
	// RVA: 0x68219f4 VA: 0x7598e399f4
	public ClipCaps get_clipCaps() { }
	// RVA: 0x68222fc VA: 0x7598e3a2fc
	internal Int32 Hash() { }
	// RVA: 0x6822540 VA: 0x7598e3a540
	public Single EvaluateMixOut(Double time) { }
	// RVA: 0x6822634 VA: 0x7598e3a634
	public Single EvaluateMixIn(Double time) { }
	// RVA: 0x6822160 VA: 0x7598e3a160
	private static AnimationCurve GetDefaultMixInCurve() { }
	// RVA: 0x6822258 VA: 0x7598e3a258
	private static AnimationCurve GetDefaultMixOutCurve() { }
	// RVA: 0x6822708 VA: 0x7598e3a708
	public Double ToLocalTime(Double time) { }
	// RVA: 0x6821af0 VA: 0x7598e39af0
	private static Double SanitizeTimeValue(Double value, Double defaultValue) { }
	// RVA: 0x68229b4 VA: 0x7598e3a9b4
	public ClipExtrapolation get_postExtrapolationMode() { }
	// RVA: 0x681de78 VA: 0x7598e35e78
	internal Void set_postExtrapolationMode(ClipExtrapolation value) { }
	// RVA: 0x68229d8 VA: 0x7598e3a9d8
	public ClipExtrapolation get_preExtrapolationMode() { }
	// RVA: 0x681de44 VA: 0x7598e35e44
	internal Void set_preExtrapolationMode(ClipExtrapolation value) { }
	// RVA: 0x68229fc VA: 0x7598e3a9fc
	internal Void SetPostExtrapolationTime(Double time) { }
	// RVA: 0x6822a04 VA: 0x7598e3aa04
	internal Void SetPreExtrapolationTime(Double time) { }
	// RVA: 0x68227f4 VA: 0x7598e3a7f4
	public Boolean IsPreExtrapolatedTime(Double sequenceTime) { }
	// RVA: 0x682295c VA: 0x7598e3a95c
	public Boolean IsPostExtrapolatedTime(Double sequenceTime) { }
	// RVA: 0x6822a0c VA: 0x7598e3aa0c
	public Double get_extrapolatedStart() { }
	// RVA: 0x6822a24 VA: 0x7598e3aa24
	public Double get_extrapolatedDuration() { }
	// RVA: 0x6822844 VA: 0x7598e3a844
	private static Double GetExtrapolatedTime(Double time, ClipExtrapolation mode, Double duration) { }
	// RVA: 0x6822af0 VA: 0x7598e3aaf0
	private Void UnityEngine.ISerializationCallbackReceiver.OnBeforeSerialize() { }
	// RVA: 0x6822afc VA: 0x7598e3aafc
	private Void UnityEngine.ISerializationCallbackReceiver.OnAfterDeserialize() { }
	// RVA: 0x6822b34 VA: 0x7598e3ab34
	public override String ToString() { }
	// RVA: 0x6821aec VA: 0x7598e39aec
	private Void UpdateDirty(Double oldValue, Double newValue) { }
	// RVA: 0x6822d4c VA: 0x7598e3ad4c
	private static Void .cctor() { }
}
```