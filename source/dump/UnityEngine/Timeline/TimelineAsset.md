# TimelineAsset

**Namespace:** `UnityEngine.Timeline`


## Fields

- `Int32 m_Version`

- `Double m_FixedDuration`

- `EditorSettings m_EditorSettings`

- `DurationMode m_DurationMode`

- `MarkerTrack m_MarkerTrack`


## Properties

- `EditorSettings editorSettings`

- `Double fixedDuration`

- `DurationMode durationMode`

- `ClipCaps clipCaps`

- `Int32 outputTrackCount`

- `Int32 rootTrackCount`

- `MarkerTrack markerTrack`


## Methods

- `Void UpgradeToLatestVersion()`

- `EditorSettings get_editorSettings()`

- `Double get_fixedDuration()`

- `Void set_fixedDuration(Double)`

- `DurationMode get_durationMode()`

- `Void set_durationMode(DurationMode)`

- `ClipCaps get_clipCaps()`

- `Int32 get_outputTrackCount()`

- `Int32 get_rootTrackCount()`

- `Void OnValidate()`

- `TrackAsset GetRootTrack(Int32)`

- `TrackAsset GetOutputTrack(Int32)`

- `Void UpdateRootTrackCache()`

- `Void UpdateOutputTrackCache()`

- `MarkerTrack get_markerTrack()`

- `Void __internalAwake()`

- `Void GatherProperties(PlayableDirector, IPropertyCollector)`

- `Void CreateMarkerTrack()`

- `DiscreteTime CalculateItemsDuration()`

- `TrackAsset CreateTrack(Type, TrackAsset, String)`

- `T CreateTrack(TrackAsset, String)`

- `T CreateTrack(String)`

- `T CreateTrack()`

- `Boolean DeleteClip(TimelineClip)`

- `Boolean DeleteTrack(TrackAsset)`

- `TrackAsset AllocateTrack(TrackAsset, String, Type)`

- `Void DeleteRecordedAnimation(TrackAsset)`

- `Void DeleteRecordedAnimation(TimelineClip)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
public class TimelineAsset : PlayableAsset, ISerializationCallbackReceiver, ITimelineClipAsset, IPropertyPreview
{
	private const Int32 k_LatestVersion; // 0x0
	private Int32 m_Version; // 0x18
	private List`1 m_Tracks; // 0x20
	private Double m_FixedDuration; // 0x28
	private TrackAsset[] m_CacheOutputTracks; // 0x30
	private List`1 m_CacheRootTracks; // 0x38
	private TrackAsset[] m_CacheFlattenedTracks; // 0x40
	private EditorSettings m_EditorSettings; // 0x48
	private DurationMode m_DurationMode; // 0x50
	private MarkerTrack m_MarkerTrack; // 0x58

	public EditorSettings editorSettings { get; }
	public override Double duration { get; }
	public Double fixedDuration { get; set; }
	public DurationMode durationMode { get; set; }
	public override IEnumerable`1 outputs { get; }
	public ClipCaps clipCaps { get; }
	public Int32 outputTrackCount { get; }
	public Int32 rootTrackCount { get; }
	internal TrackAsset[] flattenedTracks { get; }
	public MarkerTrack markerTrack { get; }
	internal List`1 trackObjects { get; }

	// RVA: 0x6822ddc VA: 0x7598e3addc
	private Void UpgradeToLatestVersion() { }
	// RVA: 0x6822de0 VA: 0x7598e3ade0
	public EditorSettings get_editorSettings() { }
	// RVA: 0x6822de8 VA: 0x7598e3ade8
	public override Double get_duration() { }
	// RVA: 0x6823088 VA: 0x7598e3b088
	public Double get_fixedDuration() { }
	// RVA: 0x6823158 VA: 0x7598e3b158
	public Void set_fixedDuration(Double value) { }
	// RVA: 0x68231c8 VA: 0x7598e3b1c8
	public DurationMode get_durationMode() { }
	// RVA: 0x68231d0 VA: 0x7598e3b1d0
	public Void set_durationMode(DurationMode value) { }
	// RVA: 0x68231d8 VA: 0x7598e3b1d8
	public override IEnumerable`1 get_outputs() { }
	// RVA: 0x6823290 VA: 0x7598e3b290
	public ClipCaps get_clipCaps() { }
	// RVA: 0x68235f8 VA: 0x7598e3b5f8
	public Int32 get_outputTrackCount() { }
	// RVA: 0x6823874 VA: 0x7598e3b874
	public Int32 get_rootTrackCount() { }
	// RVA: 0x6823c64 VA: 0x7598e3bc64
	private Void OnValidate() { }
	// RVA: 0x6823d50 VA: 0x7598e3bd50
	public TrackAsset GetRootTrack(Int32 index) { }
	// RVA: 0x68235e0 VA: 0x7598e3b5e0
	public IEnumerable`1 GetRootTracks() { }
	// RVA: 0x6823db0 VA: 0x7598e3bdb0
	public TrackAsset GetOutputTrack(Int32 index) { }
	// RVA: 0x6823df4 VA: 0x7598e3bdf4
	public IEnumerable`1 GetOutputTracks() { }
	// RVA: 0x6823c8c VA: 0x7598e3bc8c
	private static Double GetValidFrameRate(Double frameRate) { }
	// RVA: 0x68238c4 VA: 0x7598e3b8c4
	private Void UpdateRootTrackCache() { }
	// RVA: 0x682361c VA: 0x7598e3b61c
	private Void UpdateOutputTrackCache() { }
	// RVA: 0x6823e0c VA: 0x7598e3be0c
	internal TrackAsset[] get_flattenedTracks() { }
	// RVA: 0x68242c0 VA: 0x7598e3c2c0
	public MarkerTrack get_markerTrack() { }
	// RVA: 0x68242c8 VA: 0x7598e3c2c8
	internal List`1 get_trackObjects() { }
	// RVA: 0x68242d0 VA: 0x7598e3c2d0
	internal Void AddTrackInternal(TrackAsset track) { }
	// RVA: 0x68243d4 VA: 0x7598e3c3d4
	internal Void RemoveTrack(TrackAsset track) { }
	// RVA: 0x6824564 VA: 0x7598e3c564
	public override Playable CreatePlayable(PlayableGraph graph, GameObject go) { }
	// RVA: 0x6824944 VA: 0x7598e3c944
	private Void UnityEngine.ISerializationCallbackReceiver.OnBeforeSerialize() { }
	// RVA: 0x682494c VA: 0x7598e3c94c
	private Void UnityEngine.ISerializationCallbackReceiver.OnAfterDeserialize() { }
	// RVA: 0x6824950 VA: 0x7598e3c950
	private Void __internalAwake() { }
	// RVA: 0x6824ad8 VA: 0x7598e3cad8
	public Void GatherProperties(PlayableDirector director, IPropertyCollector driver) { }
	// RVA: 0x6824f80 VA: 0x7598e3cf80
	public Void CreateMarkerTrack() { }
	// RVA: 0x682439c VA: 0x7598e3c39c
	internal Void Invalidate() { }
	// RVA: 0x6825168 VA: 0x7598e3d168
	internal Void UpdateFixedDurationWithItemsDuration() { }
	// RVA: 0x6822e98 VA: 0x7598e3ae98
	private DiscreteTime CalculateItemsDuration() { }
	// RVA: 0x6823f74 VA: 0x7598e3bf74
	private static Void AddSubTracksRecursive(TrackAsset track, ref List`1 allTracks) { }
	// RVA: 0x6825304 VA: 0x7598e3d304
	public TrackAsset CreateTrack(Type type, TrackAsset parent, String name) { }
	// RVA: 0x VA: 0x0
	public T CreateTrack(TrackAsset parent, String trackName) { }
	// RVA: 0x VA: 0x0
	public T CreateTrack(String trackName) { }
	// RVA: 0x VA: 0x0
	public T CreateTrack() { }
	// RVA: 0x6826004 VA: 0x7598e3e004
	public Boolean DeleteClip(TimelineClip clip) { }
	// RVA: 0x682672c VA: 0x7598e3e72c
	public Boolean DeleteTrack(TrackAsset track) { }
	// RVA: 0x6826d8c VA: 0x7598e3ed8c
	internal Void MoveLastTrackBefore(TrackAsset asset) { }
	// RVA: 0x6825d90 VA: 0x7598e3dd90
	private TrackAsset AllocateTrack(TrackAsset trackAssetParent, String trackName, Type trackType) { }
	// RVA: 0x6826c5c VA: 0x7598e3ec5c
	private Void DeleteRecordedAnimation(TrackAsset track) { }
	// RVA: 0x6826238 VA: 0x7598e3e238
	private Void DeleteRecordedAnimation(TimelineClip clip) { }
	// RVA: 0x6827098 VA: 0x7598e3f098
	public Void .ctor() { }
}
```