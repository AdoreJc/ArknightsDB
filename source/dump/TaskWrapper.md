# TaskWrapper

**Namespace:** ` `


## Fields

- `Boolean m_isRunning`

- `Boolean m_isComplete`

- `IEnumerator m_task`


## Properties

- `Boolean isComplete`

- `Boolean isRunning`


## Methods

- `Boolean get_isComplete()`

- `Boolean get_isRunning()`

- `Void CompleteTask()`

- `Void HoldTask(IEnumerator)`

- `Coroutine StartTask(MonoBehaviour)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TaskWrapper
{
	private Boolean m_isRunning; // 0x10
	private Boolean m_isComplete; // 0x11
	private IEnumerator m_task; // 0x18

	public Boolean isComplete { get; }
	public Boolean isRunning { get; }

	// RVA: 0x40c4f30 VA: 0x75966dcf30
	public Void .ctor() { }
	// RVA: 0x40c55d8 VA: 0x75966dd5d8
	public Boolean get_isComplete() { }
	// RVA: 0x40c55e0 VA: 0x75966dd5e0
	public Boolean get_isRunning() { }
	// RVA: 0x40c55e8 VA: 0x75966dd5e8
	public Void CompleteTask() { }
	// RVA: 0x40c55f4 VA: 0x75966dd5f4
	public Void HoldTask(IEnumerator task) { }
	// RVA: 0x40c51b4 VA: 0x75966dd1b4
	public Coroutine StartTask(MonoBehaviour mono) { }
}
```