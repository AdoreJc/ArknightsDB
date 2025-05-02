# FarthestPointMovement

**Namespace:** `Torappu.Battle.Projectiles`


## Fields

- `TargetHeightType _targetHeightType`

- `Boolean _useStartDirection`

- `Boolean _useTargetDirection`

- `Boolean _withinAbilityRange`

- `Boolean _useConstDirection`

- `Direction _constDirection`

- `Boolean _useDirToTarget`

- `Boolean _removeTraceTargetAtStart`

- `Boolean _useEightWaysDirection`

- `Boolean _useTraceTargetDirection`


## Properties

- `Boolean NotUseStartDirection`

- `Boolean NotUseTargetDirection`

- `Boolean useConstDirection`

- `Direction constDirection`

- `Boolean withinAbilityRange`

- `TargetHeightType targetHeightType`


## Methods

- `Boolean get_NotUseStartDirection()`

- `Boolean get_NotUseTargetDirection()`

- `Boolean get_useConstDirection()`

- `Direction get_constDirection()`

- `Boolean get_withinAbilityRange()`

- `TargetHeightType get_targetHeightType()`

- `Void _SetTargetPosAndDirection(ILocatable, ILocatable)`

- `Void <>xLuaBaseProxy_OnInit(ILocatable, ILocatable)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Projectiles
public class FarthestPointMovement : AdvancedMovement
{
	private TargetHeightType _targetHeightType; // 0x114
	private Boolean _useStartDirection; // 0x118
	private Boolean _useTargetDirection; // 0x119
	private Boolean _withinAbilityRange; // 0x11a
	private Boolean _useConstDirection; // 0x11b
	private Direction _constDirection; // 0x11c
	private Boolean _useDirToTarget; // 0x120
	private Boolean _removeTraceTargetAtStart; // 0x121
	private Boolean _useEightWaysDirection; // 0x122
	private Boolean _useTraceTargetDirection; // 0x123
	private static DelegateBridge __Hotfix0_get_NotUseStartDirection; // 0x0
	private static DelegateBridge __Hotfix0_get_NotUseTargetDirection; // 0x8
	private static DelegateBridge __Hotfix0_get_useConstDirection; // 0x10
	private static DelegateBridge __Hotfix0_get_constDirection; // 0x18
	private static DelegateBridge __Hotfix0_get_withinAbilityRange; // 0x20
	private static DelegateBridge __Hotfix0_get_targetHeightType; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0__SetTargetPosAndDirection; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean NotUseStartDirection { get; }
	private Boolean NotUseTargetDirection { get; }
	protected Boolean useConstDirection { get; }
	protected Direction constDirection { get; }
	protected Boolean withinAbilityRange { get; }
	protected TargetHeightType targetHeightType { get; }

	// RVA: 0x1da0898 VA: 0x75943b8898
	private Boolean get_NotUseStartDirection() { }
	// RVA: 0x1da0908 VA: 0x75943b8908
	private Boolean get_NotUseTargetDirection() { }
	// RVA: 0x1da0978 VA: 0x75943b8978
	protected Boolean get_useConstDirection() { }
	// RVA: 0x1da09e0 VA: 0x75943b89e0
	protected Direction get_constDirection() { }
	// RVA: 0x1da0a48 VA: 0x75943b8a48
	protected Boolean get_withinAbilityRange() { }
	// RVA: 0x1da0ab0 VA: 0x75943b8ab0
	protected TargetHeightType get_targetHeightType() { }
	// RVA: 0x1da0b18 VA: 0x75943b8b18
	protected override Void OnInit(ILocatable start, ILocatable target) { }
	// RVA: 0x1da0bb4 VA: 0x75943b8bb4
	private Void _SetTargetPosAndDirection(ILocatable start, ILocatable target) { }
	// RVA: 0x1da14fc VA: 0x75943b94fc
	public Void .ctor() { }
	// RVA: 0x1da1570 VA: 0x75943b9570
	private Void <>xLuaBaseProxy_OnInit(ILocatable P0, ILocatable P1) { }
}
```