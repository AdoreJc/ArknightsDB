# Context

**Namespace:** `Torappu.Battle`


## Methods

- `Snapshot TakeSnapshot()`

- `ChangeGuard BeginChangeGard()`

- `Void Clear()`

- `Snapshot _DuplicateAll()`

- `Void _PopAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Context
{
	private const Int32 INITIAL_STACK_CAPACITY; // 0x0
	private ContextPtrStack`1 m_source; // 0x10
	private ContextPtrStack`1 m_target; // 0x18
	private ContextPtrStack`1 m_buff; // 0x20
	private ContextValueStack`1 m_ability; // 0x28
	private ContextValueStack`1 m_modifier; // 0x30
	private ContextPtrStack`1 m_projectile; // 0x38
	private ContextPtrStack`1 m_tile; // 0x40
	private ContextValueStack`1 m_atkInfo; // 0x48
	private ContextValueStack`1 m_mainTarget; // 0x50
	private ContextPtrStack`1 m_mainBuff; // 0x58

	public ContextPtrStack`1 source { get; }
	public ContextPtrStack`1 target { get; }
	public ContextPtrStack`1 buff { get; }
	public ContextValueStack`1 ability { get; }
	public ContextValueStack`1 modifier { get; }
	public ContextPtrStack`1 projectile { get; }
	public ContextPtrStack`1 tile { get; }
	public ContextValueStack`1 atkInfo { get; }
	public ContextValueStack`1 mainTarget { get; }
	public ContextPtrStack`1 mainBuff { get; }

	// RVA: 0x3fa6b94 VA: 0x75965beb94
	public ContextPtrStack`1 get_source() { }
	// RVA: 0x3fa6b9c VA: 0x75965beb9c
	public ContextPtrStack`1 get_target() { }
	// RVA: 0x3fa6ba4 VA: 0x75965beba4
	public ContextPtrStack`1 get_buff() { }
	// RVA: 0x3fa6bac VA: 0x75965bebac
	public ContextValueStack`1 get_ability() { }
	// RVA: 0x3fa6bb4 VA: 0x75965bebb4
	public ContextValueStack`1 get_modifier() { }
	// RVA: 0x3fa6bbc VA: 0x75965bebbc
	public ContextPtrStack`1 get_projectile() { }
	// RVA: 0x3fa6bc4 VA: 0x75965bebc4
	public ContextPtrStack`1 get_tile() { }
	// RVA: 0x3fa6bcc VA: 0x75965bebcc
	public ContextValueStack`1 get_atkInfo() { }
	// RVA: 0x3fa6bd4 VA: 0x75965bebd4
	public ContextValueStack`1 get_mainTarget() { }
	// RVA: 0x3fa6bdc VA: 0x75965bebdc
	public ContextPtrStack`1 get_mainBuff() { }
	// RVA: 0x3fa6be4 VA: 0x75965bebe4
	public Snapshot TakeSnapshot() { }
	// RVA: 0x3fa6e80 VA: 0x75965bee80
	public ChangeGuard BeginChangeGard() { }
	// RVA: 0x3fa6f30 VA: 0x75965bef30
	public Void Clear() { }
	// RVA: 0x3fa709c VA: 0x75965bf09c
	private Snapshot _DuplicateAll() { }
	// RVA: 0x3fa7350 VA: 0x75965bf350
	private Void _PopAll() { }
	// RVA: 0x3fa74d0 VA: 0x75965bf4d0
	public Void .ctor() { }
}
```