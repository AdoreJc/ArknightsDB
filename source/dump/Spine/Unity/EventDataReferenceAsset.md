# EventDataReferenceAsset

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonDataAsset skeletonDataAsset`

- `String eventName`

- `EventData eventData`


## Properties

- `EventData EventData`


## Methods

- `EventData get_EventData()`

- `Void Initialize()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class EventDataReferenceAsset : ScriptableObject
{
	private const Boolean QuietSkeletonData; // 0x0
	protected SkeletonDataAsset skeletonDataAsset; // 0x18
	protected String eventName; // 0x20
	private EventData eventData; // 0x28

	public EventData EventData { get; }

	// RVA: 0x61f8930 VA: 0x7598810930
	public EventData get_EventData() { }
	// RVA: 0x61f8954 VA: 0x7598810954
	public Void Initialize() { }
	// RVA: 0x61f8b0c VA: 0x7598810b0c
	public static EventData op_Implicit(EventDataReferenceAsset asset) { }
	// RVA: 0x61f8b38 VA: 0x7598810b38
	public Void .ctor() { }
}
```