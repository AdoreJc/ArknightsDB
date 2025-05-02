# DemoHubSample

**Namespace:** ` `


## Fields

- `Connection signalRConnection`

- `DemoHub demoHub`

- `TypedDemoHub typedDemoHub`

- `Hub vbDemoHub`

- `String vbReadStateResult`

- `Vector2 scrollPos`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void OnGUI()`

- `Void <Start>b__7_0(Connection)`

- `Void <Start>b__7_1(Hub, ClientMessage, ResultMessage)`

- `Void <OnGUI>b__9_0()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
internal class DemoHubSample : MonoBehaviour
{
	private readonly Uri URI; // 0x18
	private Connection signalRConnection; // 0x20
	private DemoHub demoHub; // 0x28
	private TypedDemoHub typedDemoHub; // 0x30
	private Hub vbDemoHub; // 0x38
	private String vbReadStateResult; // 0x40
	private Vector2 scrollPos; // 0x48


	// RVA: 0x644dd20 VA: 0x7598a65d20
	private Void Start() { }
	// RVA: 0x644e4e0 VA: 0x7598a664e0
	private Void OnDestroy() { }
	// RVA: 0x644e4fc VA: 0x7598a664fc
	private Void OnGUI() { }
	// RVA: 0x644e5cc VA: 0x7598a665cc
	public Void .ctor() { }
	// RVA: 0x644e684 VA: 0x7598a66684
	private Void <Start>b__7_0(Connection connection) { }
	// RVA: 0x644fb04 VA: 0x7598a67b04
	private Void <Start>b__7_1(Hub hub, ClientMessage msg, ResultMessage result) { }
	// RVA: 0x644fba4 VA: 0x7598a67ba4
	private Void <OnGUI>b__9_0() { }
}
```