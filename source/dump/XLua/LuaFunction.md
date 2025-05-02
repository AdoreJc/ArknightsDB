# LuaFunction

**Namespace:** `XLua`


## Methods

- `Void Action(T)`

- `TResult Func(T)`

- `Void Action(T1, T2)`

- `TResult Func(T1, T2)`

- `T Cast()`

- `Void SetEnv(LuaTable)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class LuaFunction : LuaBase
{


	// RVA: 0x3edc958 VA: 0x75964f4958
	public Void .ctor(Int32 reference, LuaEnv luaenv) { }
	// RVA: 0x VA: 0x0
	public Void Action(T a) { }
	// RVA: 0x VA: 0x0
	public TResult Func(T a) { }
	// RVA: 0x VA: 0x0
	public Void Action(T1 a1, T2 a2) { }
	// RVA: 0x VA: 0x0
	public TResult Func(T1 a1, T2 a2) { }
	// RVA: 0x3edc990 VA: 0x75964f4990
	public Object[] Call(Object[] args, Type[] returnTypes) { }
	// RVA: 0x3edcc08 VA: 0x75964f4c08
	public Object[] Call(Object[] args) { }
	// RVA: 0x VA: 0x0
	public T Cast() { }
	// RVA: 0x3edcc10 VA: 0x75964f4c10
	public Void SetEnv(LuaTable env) { }
	// RVA: 0x3edcd6c VA: 0x75964f4d6c
	internal override Void push(IntPtr L) { }
	// RVA: 0x3edcd80 VA: 0x75964f4d80
	public override String ToString() { }
}
```