# CrisisV2FocusModel

**Namespace:** ` `


## Fields

- `Int32 m_interactId`

- `Int32 m_tipsSeqNum`

- `ActionType m_actionType`

- `TargetType m_targetType`

- `String m_targetId`


## Properties

- `Int32 interactId`

- `Int32 tipsSeqNum`

- `ActionType actionType`

- `TargetType targetType`

- `String targetId`


## Methods

- `Int32 get_interactId()`

- `Int32 get_tipsSeqNum()`

- `ActionType get_actionType()`

- `TargetType get_targetType()`

- `String get_targetId()`

- `Void FoucusOn(TargetType, String, ActionType)`

- `Void _UpdateTipsSeqNumIfNecessary()`

- `Boolean IsEmpty()`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2FocusModel : IHotfixable
{
	private Int32 m_interactId; // 0x10
	private Int32 m_tipsSeqNum; // 0x14
	private ActionType m_actionType; // 0x18
	private TargetType m_targetType; // 0x1c
	private String m_targetId; // 0x20
	private static DelegateBridge __Hotfix0_get_interactId; // 0x0
	private static DelegateBridge __Hotfix0_get_tipsSeqNum; // 0x8
	private static DelegateBridge __Hotfix0_get_actionType; // 0x10
	private static DelegateBridge __Hotfix0_get_targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_targetId; // 0x20
	private static DelegateBridge __Hotfix0_FoucusOn; // 0x28
	private static DelegateBridge __Hotfix0__UpdateTipsSeqNumIfNecessary; // 0x30
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x38
	private static DelegateBridge __Hotfix0_Clear; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 interactId { get; }
	public Int32 tipsSeqNum { get; }
	public ActionType actionType { get; }
	public TargetType targetType { get; }
	public String targetId { get; }

	// RVA: 0x2be9cac VA: 0x7595201cac
	public Int32 get_interactId() { }
	// RVA: 0x2be9d84 VA: 0x7595201d84
	public Int32 get_tipsSeqNum() { }
	// RVA: 0x2beb08c VA: 0x759520308c
	public ActionType get_actionType() { }
	// RVA: 0x2be9820 VA: 0x7595201820
	public TargetType get_targetType() { }
	// RVA: 0x2be9888 VA: 0x7595201888
	public String get_targetId() { }
	// RVA: 0x2bea058 VA: 0x7595202058
	public Void FoucusOn(TargetType targetType, String targetId, ActionType actionType) { }
	// RVA: 0x2bf2e98 VA: 0x759520ae98
	private Void _UpdateTipsSeqNumIfNecessary() { }
	// RVA: 0x2be9794 VA: 0x7595201794
	public Boolean IsEmpty() { }
	// RVA: 0x2beb9d0 VA: 0x75952039d0
	public Void Clear() { }
	// RVA: 0x2bf2d68 VA: 0x759520ad68
	public Void .ctor() { }
}
```