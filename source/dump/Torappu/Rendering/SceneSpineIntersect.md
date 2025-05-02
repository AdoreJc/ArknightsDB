# SceneSpineIntersect

**Namespace:** `Torappu.Rendering`


## Fields

- `SceneSpineIntersectProfile _profile`

- `Single _intersectHeight`


## Properties

- `Boolean intersectEnabled`


## Methods

- `Boolean get_intersectEnabled()`

- `Void Update()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Shader <>xLuaBaseProxy_GetReplaceSpineShader()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class SceneSpineIntersect : BaseSceneEffect
{
	private SceneSpineIntersectProfile _profile; // 0x18
	private Single _intersectHeight; // 0x20
	private static DelegateBridge __Hotfix0_get_intersectEnabled; // 0x0
	private static DelegateBridge __Hotfix0_GetReplaceSpineShader; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_OnEnable; // 0x18
	private static DelegateBridge __Hotfix0_OnDisable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Boolean intersectEnabled { get; }

	// RVA: 0x3f090c4 VA: 0x75965210c4
	private Boolean get_intersectEnabled() { }
	// RVA: 0x3f091a0 VA: 0x75965211a0
	public override Shader GetReplaceSpineShader() { }
	// RVA: 0x3f09228 VA: 0x7596521228
	private Void Update() { }
	// RVA: 0x3f092c4 VA: 0x75965212c4
	private Void OnEnable() { }
	// RVA: 0x3f093f4 VA: 0x75965213f4
	private Void OnDisable() { }
	// RVA: 0x3f0948c VA: 0x759652148c
	public Void .ctor() { }
	// RVA: 0x3f094f8 VA: 0x75965214f8
	private Shader <>xLuaBaseProxy_GetReplaceSpineShader() { }
}
```