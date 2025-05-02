# InvokeWhenUnlock

**Namespace:** ` `


## Fields

- `Boolean m_unlocked`

- `Action m_callback`


## Methods

- `Void Unlock()`

- `Void Invoke(Action)`

- `Boolean IsUnlocked()`

- `Void ForgetAndLock()`

- `Void _ConsumeIfUnlocked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InvokeWhenUnlock
{
	private Boolean m_unlocked; // 0x10
	private Action m_callback; // 0x18


	// RVA: 0x3115c5c VA: 0x759572dc5c
	public Void Unlock() { }
	// RVA: 0x3115c94 VA: 0x759572dc94
	public Void Invoke(Action callback) { }
	// RVA: 0x3115d90 VA: 0x759572dd90
	public Boolean IsUnlocked() { }
	// RVA: 0x3115d98 VA: 0x759572dd98
	public Void ForgetAndLock() { }
	// RVA: 0x3115d4c VA: 0x759572dd4c
	private Void _ConsumeIfUnlocked() { }
	// RVA: 0x3115dbc VA: 0x759572ddbc
	public Void .ctor() { }
}
```