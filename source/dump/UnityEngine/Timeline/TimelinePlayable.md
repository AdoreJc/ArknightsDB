# TimelinePlayable

**Namespace:** `UnityEngine.Timeline`


## Fields

- `Int32 m_ActiveBit`


## Methods

- `Void Compile(PlayableGraph, Playable, IEnumerable`1, GameObject, Boolean, Boolean)`

- `Void CompileTrackList(PlayableGraph, Playable, IEnumerable`1, GameObject, Boolean)`

- `Void CreateTrackOutput(PlayableGraph, TrackAsset, GameObject, Playable, Int32)`

- `Void EvaluateWeightsForAnimationPlayableOutput(TrackAsset, AnimationPlayableOutput)`

- `Playable CreateTrackPlayable(PlayableGraph, Playable, TrackAsset, GameObject, Boolean)`

- `Void Evaluate(Playable, FrameData)`

- `Void CacheTrack(TrackAsset, Playable, Int32, Playable)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
public class TimelinePlayable : PlayableBehaviour
{
	private IntervalTree`1 m_IntervalTree; // 0x10
	private List`1 m_ActiveClips; // 0x18
	private List`1 m_CurrentListOfActiveClips; // 0x20
	private Int32 m_ActiveBit; // 0x28
	private List`1 m_EvaluateCallbacks; // 0x30
	private Dictionary`2 m_PlayableCache; // 0x38
	internal static Boolean muteAudioScrubbing; // 0x0


	// RVA: 0x6824724 VA: 0x7598e3c724
	public static ScriptPlayable`1 Create(PlayableGraph graph, IEnumerable`1 tracks, GameObject go, Boolean autoRebalance, Boolean createOutputs) { }
	// RVA: 0x683132c VA: 0x7598e4932c
	public Void Compile(PlayableGraph graph, Playable timelinePlayable, IEnumerable`1 tracks, GameObject go, Boolean autoRebalance, Boolean createOutputs) { }
	// RVA: 0x68315d8 VA: 0x7598e495d8
	private Void CompileTrackList(PlayableGraph graph, Playable timelinePlayable, IEnumerable`1 tracks, GameObject go, Boolean createOutputs) { }
	// RVA: 0x6831d84 VA: 0x7598e49d84
	private Void CreateTrackOutput(PlayableGraph graph, TrackAsset track, GameObject go, Playable playable, Int32 port) { }
	// RVA: 0x683244c VA: 0x7598e4a44c
	private Void EvaluateWeightsForAnimationPlayableOutput(TrackAsset track, AnimationPlayableOutput animOutput) { }
	// RVA: 0x683196c VA: 0x7598e4996c
	private Playable CreateTrackPlayable(PlayableGraph graph, Playable timelinePlayable, TrackAsset track, GameObject go, Boolean createOutputs) { }
	// RVA: 0x68325ac VA: 0x7598e4a5ac
	public override Void PrepareFrame(Playable playable, FrameData info) { }
	// RVA: 0x68325d8 VA: 0x7598e4a5d8
	private Void Evaluate(Playable playable, FrameData frameData) { }
	// RVA: 0x683253c VA: 0x7598e4a53c
	private Void CacheTrack(TrackAsset track, Playable playable, Int32 port, Playable parent) { }
	// RVA: 0x6832bbc VA: 0x7598e4abbc
	public Void .ctor() { }
	// RVA: 0x6832d34 VA: 0x7598e4ad34
	private static Void .cctor() { }
}
```