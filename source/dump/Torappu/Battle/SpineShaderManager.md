# SpineShaderManager

**Namespace:** `Torappu.Battle`


## Fields

- `ReplaceOptions m_replaceOptions`

- `Boolean m_shaderReplaced`

- `Shader m_defaultOriginShader`


## Methods

- `Void OnSceneEffectInit(ReplaceOptions)`

- `Boolean CheckGlobalSpineShaderReplacement(Material, Shader, out)`

- `Boolean CheckTileSpineShaderReplacement(Vector2, Material, MaterialPropertyBlock, Shader, out)`

- `Void ResetSpineShader(Material)`

- `Void ResetAllSpineShaders()`

- `Boolean _CheckSpineInTilePos(Vector2)`

- `Shader _FindDefaultSpineShader()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SpineShaderManager
{
	private ReplaceOptions m_replaceOptions; // 0x10
	private Boolean m_shaderReplaced; // 0x28
	private Shader m_defaultOriginShader; // 0x30
	private ListDict`2 m_originShaderMap; // 0x38


	// RVA: 0x3f5d73c VA: 0x759657573c
	public Void OnSceneEffectInit(ReplaceOptions options) { }
	// RVA: 0x3f5af24 VA: 0x7596572f24
	public Boolean CheckGlobalSpineShaderReplacement(Material sharedMat, Shader originShader, out Shader replaceShader) { }
	// RVA: 0x3f5b068 VA: 0x7596573068
	public Boolean CheckTileSpineShaderReplacement(Vector2 tileWorldPos, Material sharedMat, MaterialPropertyBlock materialBlock, Shader originShader, out Shader replaceShader) { }
	// RVA: 0x3f5b43c VA: 0x759657343c
	public Void ResetSpineShader(Material sharedMat) { }
	// RVA: 0x3f5dca4 VA: 0x7596575ca4
	public Void ResetAllSpineShaders() { }
	// RVA: 0x3f5d910 VA: 0x7596575910
	private Boolean _CheckSpineInTilePos(Vector2 spineTilePos) { }
	// RVA: 0x3f5d874 VA: 0x7596575874
	private Shader _FindDefaultSpineShader() { }
	// RVA: 0x3f5de9c VA: 0x7596575e9c
	public Void .ctor() { }
}
```