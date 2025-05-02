# RetryPolicy

**Namespace:** ` `


## Fields

- `Single _initRetryDelay`

- `Single _maxRetryCnt`

- `Single _maxRetryDelay`

- `Int32 _retryCntToDoubleDelay`

- `Boolean m_inited`

- `Single m_curDelay`

- `Int32 m_curRetryCnt`


## Properties

- `Single initRetryDelay`


## Methods

- `Single get_initRetryDelay()`

- `Void Reset()`

- `Boolean TryGetNextDelay(Boolean, out)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RetryPolicy
{
	private Single _initRetryDelay; // 0x10
	private Single _maxRetryCnt; // 0x14
	private Single _maxRetryDelay; // 0x18
	private Int32 _retryCntToDoubleDelay; // 0x1c
	private Boolean m_inited; // 0x20
	private Single m_curDelay; // 0x24
	private Int32 m_curRetryCnt; // 0x28

	public Single initRetryDelay { get; }

	// RVA: 0x27c0158 VA: 0x7594dd8158
	public Single get_initRetryDelay() { }
	// RVA: 0x27c0160 VA: 0x7594dd8160
	public Void Reset() { }
	// RVA: 0x27c0194 VA: 0x7594dd8194
	public Boolean TryGetNextDelay(Boolean isTrivialError, out Single delay) { }
	// RVA: 0x27c0174 VA: 0x7594dd8174
	private Void _InitIfNot() { }
	// RVA: 0x27c0098 VA: 0x7594dd8098
	public Void .ctor() { }
}
```