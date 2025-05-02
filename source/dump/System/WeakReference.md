# WeakReference

**Namespace:** `System`


## Fields

- `Boolean isLongReference`

- `GCHandle gcHandle`


## Methods

- `Void AllocateHandle(Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class WeakReference : ISerializable
{
	private Boolean isLongReference; // 0x10
	private GCHandle gcHandle; // 0x18

	public virtual Boolean IsAlive { get; }
	public virtual Object Target { get; set; }
	public virtual Boolean TrackResurrection { get; }

	// RVA: 0x610fde8 VA: 0x7598727de8
	private Void AllocateHandle(Object target) { }
	// RVA: 0x610fe10 VA: 0x7598727e10
	protected Void .ctor() { }
	// RVA: 0x610fe18 VA: 0x7598727e18
	public Void .ctor(Object target) { }
	// RVA: 0x610fe48 VA: 0x7598727e48
	public Void .ctor(Object target, Boolean trackResurrection) { }
	// RVA: 0x610fe7c VA: 0x7598727e7c
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x610ffb4 VA: 0x7598727fb4
	public virtual Boolean get_IsAlive() { }
	// RVA: 0x610ffd4 VA: 0x7598727fd4
	public virtual Object get_Target() { }
	// RVA: 0x6110008 VA: 0x7598728008
	public virtual Void set_Target(Object value) { }
	// RVA: 0x6110014 VA: 0x7598728014
	public virtual Boolean get_TrackResurrection() { }
	// RVA: 0x611001c VA: 0x759872801c
	protected override Void Finalize() { }
	// RVA: 0x61100b8 VA: 0x75987280b8
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
}
```