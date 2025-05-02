# Manager

**Namespace:** ` `


## Fields

- `Boolean m_isInGame`


## Methods

- `GameInOutObserver CreateObserver(Callback)`

- `Void ReleaseObserver(GameInOutObserver)`

- `Void Init(String)`

- `Void BeforeGameSceneTransition(String, String)`

- `Void _NotifyInOutGame()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class Manager
{
	private readonly HashSet`1 m_observers; // 0x10
	private readonly List`1 m_buffer; // 0x18
	private Boolean m_isInGame; // 0x20


	// RVA: 0x674b620 VA: 0x7598d63620
	public GameInOutObserver CreateObserver(Callback callback) { }
	// RVA: 0x674b4c8 VA: 0x7598d634c8
	public Void ReleaseObserver(GameInOutObserver observer) { }
	// RVA: 0x674b6dc VA: 0x7598d636dc
	public Void Init(String scene) { }
	// RVA: 0x674ba04 VA: 0x7598d63a04
	public Void BeforeGameSceneTransition(String from, String to) { }
	// RVA: 0x674b7f0 VA: 0x7598d637f0
	private Void _NotifyInOutGame() { }
	// RVA: 0x674ba90 VA: 0x7598d63a90
	public Void .ctor() { }
}
```