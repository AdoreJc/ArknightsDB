# WaitForAsyncTask

**Namespace:** `Torappu`


## Fields

- `Result m_result`

- `Boolean m_isFinished`

- `Exception m_exception`


## Properties

- `Result result`

- `Exception exception`


## Methods

- `Result get_result()`

- `Exception get_exception()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class WaitForAsyncTask`1 : CustomYieldInstruction
{
	private Result m_result; // 0x0
	private Boolean m_isFinished; // 0x0
	private Exception m_exception; // 0x0

	public Result result { get; }
	public Exception exception { get; }
	public override Boolean keepWaiting { get; }

	// RVA: 0x VA: 0x0
	public Result get_result() { }
	// RVA: 0x VA: 0x0
	public Exception get_exception() { }
	// RVA: 0x VA: 0x0
	public override Boolean get_keepWaiting() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(Func`1 task) { }
}
```