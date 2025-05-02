# IDObserver

**Namespace:** ` `


## Fields

- `Object m_context`

- `TrackChangeCallback m_callback`

- `String <id>k__BackingField`


## Properties

- `String id`


## Methods

- `String get_id()`

- `Void set_id(String)`

- `Void CenterOnly_Init(String, String, TrackChangeCallback, Object)`

- `Void OnTrackStateChanged(String, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class IDObserver : ITrackObserver, IHotfixable
{
	private String[] m_typeArray; // 0x10
	private Object m_context; // 0x18
	private TrackChangeCallback m_callback; // 0x20
	private String <id>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_id; // 0x0
	private static DelegateBridge __Hotfix0_set_id; // 0x8
	private static DelegateBridge __Hotfix0_CenterOnly_Init; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0_ConcernedTypes; // 0x20
	private static DelegateBridge __Hotfix0_OnTrackStateChanged; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String id { get; set; }

	// RVA: 0x2f3ee34 VA: 0x7595556e34
	public String get_id() { }
	// RVA: 0x2f3ee9c VA: 0x7595556e9c
	private Void set_id(String value) { }
	// RVA: 0x2f3e040 VA: 0x7595556040
	public Void CenterOnly_Init(String type, String id, TrackChangeCallback callback, Object context) { }
	// RVA: 0x2f3ef20 VA: 0x7595556f20
	public static Void Reset(IDObserver inst) { }
	// RVA: 0x2f3edcc VA: 0x7595556dcc
	public IList`1 ConcernedTypes() { }
	// RVA: 0x2f3e438 VA: 0x7595556438
	public Void OnTrackStateChanged(String type, String id, Boolean exists) { }
	// RVA: 0x2f3efa8 VA: 0x7595556fa8
	public Void .ctor() { }
}
```