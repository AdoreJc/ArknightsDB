# NetSerializer

**Namespace:** `FlyingWormConsole3.LiteNetLib.Utils`


## Fields

- `NetDataWriter _writer`


## Methods

- `Void RegisterNestedType()`

- `Void RegisterNestedType(Func`1)`

- `Void RegisterNestedType(Action`2, Func`2)`

- `Void Register()`

- `T Deserialize(NetDataReader)`

- `Boolean Deserialize(NetDataReader, T)`

- `Void Serialize(NetDataWriter, T)`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib.Utils
public class NetSerializer
{
	private NetDataWriter _writer; // 0x10
	private readonly Int32 _maxStringLength; // 0x18
	private readonly Dictionary`2 _registeredTypes; // 0x20


	// RVA: 0x VA: 0x0
	public Void RegisterNestedType() { }
	// RVA: 0x VA: 0x0
	public Void RegisterNestedType(Func`1 constructor) { }
	// RVA: 0x VA: 0x0
	public Void RegisterNestedType(Action`2 writer, Func`2 reader) { }
	// RVA: 0x410a5d4 VA: 0x75967225d4
	public Void .ctor() { }
	// RVA: 0x410a6e8 VA: 0x75967226e8
	public Void .ctor(Int32 maxStringLength) { }
	// RVA: 0x VA: 0x0
	private ClassInfo`1 RegisterInternal() { }
	// RVA: 0x VA: 0x0
	public Void Register() { }
	// RVA: 0x VA: 0x0
	public T Deserialize(NetDataReader reader) { }
	// RVA: 0x VA: 0x0
	public Boolean Deserialize(NetDataReader reader, T target) { }
	// RVA: 0x VA: 0x0
	public Void Serialize(NetDataWriter writer, T obj) { }
	// RVA: 0x VA: 0x0
	public Byte[] Serialize(T obj) { }
}
```