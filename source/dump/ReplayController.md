# ReplayController

**Namespace:** ` `


## Fields

- `Boolean m_isEarlyFinished`

- `Options m_options`

- `Journal m_journal`

- `FP m_playTimeCheckCorrection`

- `Boolean <isEnabled>k__BackingField`


## Properties

- `Boolean isEnabled`

- `Int32 savedRemainingLifePoint`

- `Boolean hasUnsyncLogs`


## Methods

- `Boolean get_isEnabled()`

- `Void set_isEnabled(Boolean)`

- `Int32 get_savedRemainingLifePoint()`

- `Void Tick(FP)`

- `Boolean get_hasUnsyncLogs()`

- `Void Cancel()`

- `Boolean _TryExecuteOperation(LogItem, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ReplayController
{
	private Boolean m_isEarlyFinished; // 0x10
	private Options m_options; // 0x11
	private Journal m_journal; // 0x18
	private Queue`1 m_pendingLogs; // 0x70
	private List`1 m_readyLogs; // 0x78
	private FP m_playTimeCheckCorrection; // 0x80
	private Boolean <isEnabled>k__BackingField; // 0x88

	public Boolean isEnabled { get; set; }
	public Int32 savedRemainingLifePoint { get; }
	public Boolean hasUnsyncLogs { get; }

	// RVA: 0x3f6b7bc VA: 0x75965837bc
	public Boolean get_isEnabled() { }
	// RVA: 0x3f6b7c4 VA: 0x75965837c4
	private Void set_isEnabled(Boolean value) { }
	// RVA: 0x3f6b7d0 VA: 0x75965837d0
	public Int32 get_savedRemainingLifePoint() { }
	// RVA: 0x3f6b7d8 VA: 0x75965837d8
	public Void .ctor(Journal journal, Options options) { }
	// RVA: 0x3f6b9f0 VA: 0x75965839f0
	public Void Tick(FP playTime) { }
	// RVA: 0x3f6c2b0 VA: 0x75965842b0
	public Boolean get_hasUnsyncLogs() { }
	// RVA: 0x3f6c300 VA: 0x7596584300
	public Void Cancel() { }
	// RVA: 0x3f6be64 VA: 0x7596583e64
	private Boolean _TryExecuteOperation(LogItem log, ref Int32 indexInReadyLogsQueue) { }
}
```