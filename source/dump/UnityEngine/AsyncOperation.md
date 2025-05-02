# AsyncOperation

**Namespace:** `UnityEngine`


## Properties

- `Boolean isDone`

- `Single progress`

- `Boolean allowSceneActivation`


## Methods

- `Boolean get_isDone()`

- `Single get_progress()`

- `Void set_allowSceneActivation(Boolean)`

- `Void add_completed(Action`1)`

- `Void remove_completed(Action`1)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class AsyncOperation : YieldInstruction
{
	internal IntPtr m_Ptr; // 0x10
	private Action`1 m_completeCallback; // 0x18

	public Boolean isDone { get; }
	public Single progress { get; }
	public Boolean allowSceneActivation { set; }

	// RVA: 0x68820a8 VA: 0x7598e9a0a8
	private static Void InternalDestroy(IntPtr ptr) { }
	// RVA: 0x68820e4 VA: 0x7598e9a0e4
	public Boolean get_isDone() { }
	// RVA: 0x6882120 VA: 0x7598e9a120
	public Single get_progress() { }
	// RVA: 0x688215c VA: 0x7598e9a15c
	public Void set_allowSceneActivation(Boolean value) { }
	// RVA: 0x68821a0 VA: 0x7598e9a1a0
	protected override Void Finalize() { }
	// RVA: 0x688225c VA: 0x7598e9a25c
	internal Void InvokeCompletionEvent() { }
	// RVA: 0x68822ac VA: 0x7598e9a2ac
	public Void add_completed(Action`1 value) { }
	// RVA: 0x68823a8 VA: 0x7598e9a3a8
	public Void remove_completed(Action`1 value) { }
	// RVA: 0x68815d8 VA: 0x7598e995d8
	public Void .ctor() { }
}
```