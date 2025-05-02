# HGSceneTileWaterEffect

**Namespace:** `Torappu.Rendering`


## Methods

- `Shader <>xLuaBaseProxy_GetReplaceSpineShader()`

- `Boolean <>xLuaBaseProxy_TryGetTileReplaceSpineShader(out, out)`

- `String <>xLuaBaseProxy_GetSpineOnTileFlagName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Rendering
public class HGSceneTileWaterEffect : HGSceneWaterEffect
{
	public List`1 _waterIntersectTiles; // 0xa8
	private static DelegateBridge __Hotfix0_GetReplaceSpineShader; // 0x0
	private static DelegateBridge __Hotfix0_TryGetTileReplaceSpineShader; // 0x8
	private static DelegateBridge __Hotfix0_GetSpineOnTileFlagName; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f09964 VA: 0x7596521964
	public override Shader GetReplaceSpineShader() { }
	// RVA: 0x3f099c8 VA: 0x75965219c8
	public override Boolean TryGetTileReplaceSpineShader(out Shader replaceShader, out IList`1 tilePosList) { }
	// RVA: 0x3f09d6c VA: 0x7596521d6c
	public override String GetSpineOnTileFlagName() { }
	// RVA: 0x3f09de8 VA: 0x7596521de8
	public Void .ctor() { }
	// RVA: 0x3f09eac VA: 0x7596521eac
	private Shader <>xLuaBaseProxy_GetReplaceSpineShader() { }
	// RVA: 0x3f09eb4 VA: 0x7596521eb4
	private Boolean <>xLuaBaseProxy_TryGetTileReplaceSpineShader(out Shader P0, out IList`1 P1) { }
	// RVA: 0x3f09eb8 VA: 0x7596521eb8
	private String <>xLuaBaseProxy_GetSpineOnTileFlagName() { }
}
```