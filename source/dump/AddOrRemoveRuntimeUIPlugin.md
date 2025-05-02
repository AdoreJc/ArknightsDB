# AddOrRemoveRuntimeUIPlugin

**Namespace:** ` `


## Fields

- `Boolean _isRemove`

- `String _name`

- `String _playAudio`

- `RtUIPluginPosition _position`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddOrRemoveRuntimeUIPlugin : ActionNode
{
	private Boolean _isRemove; // 0x10
	private String _name; // 0x18
	private String _playAudio; // 0x20
	private RtUIPluginPosition _position; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fda1ec VA: 0x75945f21ec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fda254 VA: 0x75945f2254
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fda3f8 VA: 0x75945f23f8
	public Void .ctor() { }
}
```