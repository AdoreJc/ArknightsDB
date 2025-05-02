# SandboxCheckCurrentMode

**Namespace:** ` `


## Fields

- `Boolean _checkBuildMode`

- `Boolean _checkNodeType`

- `SandboxV2NodeType _sandboxNodeTypeV2`

- `Boolean _checkSeasonType`

- `SandboxV2SeasonType _sandboxSeasonTypeV2`

- `Boolean _checkWeatherType`

- `String _sandboxWeatherType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SandboxCheckCurrentMode : ActionNode
{
	private Boolean _checkBuildMode; // 0x10
	private Boolean _checkNodeType; // 0x11
	private SandboxV2NodeType _sandboxNodeTypeV2; // 0x14
	private Boolean _checkSeasonType; // 0x18
	private SandboxV2SeasonType _sandboxSeasonTypeV2; // 0x1c
	private Boolean _checkWeatherType; // 0x20
	private String _sandboxWeatherType; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f85320 VA: 0x759459d320
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f85388 VA: 0x759459d388
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f854f8 VA: 0x759459d4f8
	public Void .ctor() { }
}
```