# PlayableDirector

**Namespace:** `UnityEngine.Playables`


## Properties

- `PlayState state`

- `DirectorWrapMode extrapolationMode`

- `PlayableGraph playableGraph`

- `Double time`


## Methods

- `PlayState get_state()`

- `DirectorWrapMode get_extrapolationMode()`

- `PlayableGraph get_playableGraph()`

- `Void SetGenericBinding(Object, Object)`

- `Double get_time()`

- `Object GetGenericBinding(Object)`

- `PlayState GetPlayState()`

- `DirectorWrapMode GetWrapMode()`

- `PlayableGraph GetGraphHandle()`

- `Void Internal_SetGenericBinding(Object, Object)`

- `Void SendOnPlayableDirectorPlay()`

- `Void SendOnPlayableDirectorPause()`

- `Void SendOnPlayableDirectorStop()`

- `Void GetGraphHandle_Injected(out)`


## Dump
```C#
// Dll : UnityEngine.DirectorModule.dll
// Namespace : UnityEngine.Playables
public class PlayableDirector : Behaviour
{
	private Action`1 played; // 0x18
	private Action`1 paused; // 0x20
	private Action`1 stopped; // 0x28

	public PlayState state { get; }
	public DirectorWrapMode extrapolationMode { get; }
	public PlayableGraph playableGraph { get; }
	public Double time { get; }

	// RVA: 0x68a9e88 VA: 0x7598ec1e88
	public PlayState get_state() { }
	// RVA: 0x68a9f00 VA: 0x7598ec1f00
	public DirectorWrapMode get_extrapolationMode() { }
	// RVA: 0x68a9f78 VA: 0x7598ec1f78
	public PlayableGraph get_playableGraph() { }
	// RVA: 0x68a9fd0 VA: 0x7598ec1fd0
	public Void SetGenericBinding(Object key, Object value) { }
	// RVA: 0x68aa078 VA: 0x7598ec2078
	public Double get_time() { }
	// RVA: 0x68aa0b4 VA: 0x7598ec20b4
	public Object GetGenericBinding(Object key) { }
	// RVA: 0x68a9ec4 VA: 0x7598ec1ec4
	private PlayState GetPlayState() { }
	// RVA: 0x68a9f3c VA: 0x7598ec1f3c
	private DirectorWrapMode GetWrapMode() { }
	// RVA: 0x68a9f7c VA: 0x7598ec1f7c
	private PlayableGraph GetGraphHandle() { }
	// RVA: 0x68aa024 VA: 0x7598ec2024
	private Void Internal_SetGenericBinding(Object key, Object value) { }
	// RVA: 0x68aa13c VA: 0x7598ec213c
	private Void SendOnPlayableDirectorPlay() { }
	// RVA: 0x68aa15c VA: 0x7598ec215c
	private Void SendOnPlayableDirectorPause() { }
	// RVA: 0x68aa17c VA: 0x7598ec217c
	private Void SendOnPlayableDirectorStop() { }
	// RVA: 0x68aa0f8 VA: 0x7598ec20f8
	private Void GetGraphHandle_Injected(out PlayableGraph ret) { }
}
```