# BaseCreateCardBuff

**Namespace:** ` `


## Fields

- `LifeType _lifeType`

- `Boolean _isRatio`

- `Boolean _enableMaxStackCount`

- `Boolean _filterIsInHand`

- `Boolean _useCardBuffKey`

- `String _cardBuffKey`


## Properties

- `String cardBuffKey`

- `LifeType lifeType`

- `Boolean isRatio`


## Methods

- `String get_cardBuffKey()`

- `LifeType get_lifeType()`

- `Boolean get_isRatio()`

- `Void DoCreateCardBuff(Buff, Blackboard, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BaseCreateCardBuff : ActionNode
{
	private LifeType _lifeType; // 0x10
	private Boolean _isRatio; // 0x14
	private Boolean _enableMaxStackCount; // 0x15
	private Boolean _filterIsInHand; // 0x16
	private Boolean _useCardBuffKey; // 0x17
	private String _cardBuffKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_cardBuffKey; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge __Hotfix0_get_lifeType; // 0x18
	private static DelegateBridge __Hotfix0_get_isRatio; // 0x20
	private static DelegateBridge __Hotfix0_DoCreateCardBuff; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override SourceType allowedSource { get; }
	protected String cardBuffKey { get; }
	protected LifeType lifeType { get; }
	protected Boolean isRatio { get; }

	// RVA: 0x1f06b24 VA: 0x759451eb24
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f07d38 VA: 0x759451fd38
	protected String get_cardBuffKey() { }
	// RVA: 0x1f06b90 VA: 0x759451eb90
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f07da0 VA: 0x759451fda0
	protected LifeType get_lifeType() { }
	// RVA: 0x1f07e08 VA: 0x759451fe08
	protected Boolean get_isRatio() { }
	// RVA: 0x1f06894 VA: 0x759451e894
	protected Void DoCreateCardBuff(Buff sourceBuff, Blackboard blackboard, Card card) { }
	// RVA: 0x1f06ab0 VA: 0x759451eab0
	public Void .ctor() { }
}
```