# PrtsErrorMetaController

**Namespace:** ` `


## Fields

- `AVGTypeWriterText m_prtsErrorWriter`

- `Int32 m_prtsErrorMsgIndex`

- `Single m_interval`

- `PeriodicTimer m_timer`

- `Int32 m_line`

- `Int32 m_Maxline`

- `UILifePoint m_lifePoint`


## Methods

- `Void Init(String, Single, Int32)`

- `Void OnTick(FP)`

- `Void _DoPrtsMetaErrorMsg()`

- `Void _OnPrtsMetaErrorMsgShowedLine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PrtsErrorMetaController
{
	private AVGTypeWriterText m_prtsErrorWriter; // 0x10
	private List`1 m_prtsErrorMsg; // 0x18
	private Queue`1 m_prtsErrorMsgShowed; // 0x20
	private Int32 m_prtsErrorMsgIndex; // 0x28
	private Single m_interval; // 0x2c
	private PeriodicTimer m_timer; // 0x30
	private Int32 m_line; // 0x38
	private Int32 m_Maxline; // 0x3c
	public UILifePoint m_lifePoint; // 0x40


	// RVA: 0x40584ec VA: 0x75966704ec
	public Void Init(String prtsErrorUIPlugin, Single prtsWriterInterval, Int32 _prtsWriterMaxLine) { }
	// RVA: 0x4057848 VA: 0x759666f848
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x405a61c VA: 0x759667261c
	private Void _DoPrtsMetaErrorMsg() { }
	// RVA: 0x405a7c4 VA: 0x75966727c4
	private Void _OnPrtsMetaErrorMsgShowedLine() { }
	// RVA: 0x40584e4 VA: 0x75966704e4
	public Void .ctor() { }
}
```