# StageEditButtonHolderPatch

**Namespace:** `Torappu.UI.Stage.Test`


## Fields

- `String _sourceAssetPath`

- `String _sourceTypeName`

- `StageButtonPatch _prevPatch`

- `String lineToStageId`


## Methods

- `Void Init(IStageButtonPatchCollection, StageButtonPatch)`

- `Void SaveToSource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.Test
public class StageEditButtonHolderPatch : MonoBehaviour
{
	private const String ERROR_RESOLVE_METHOD; // 0x0
	private String _sourceAssetPath; // 0x18
	private String _sourceTypeName; // 0x20
	private StageButtonPatch _prevPatch; // 0x28
	public String lineToStageId; // 0x48


	// RVA: 0x2fe04cc VA: 0x75955f84cc
	public Void Init(IStageButtonPatchCollection source, StageButtonPatch patch) { }
	// RVA: 0x2fe04d0 VA: 0x75955f84d0
	public Void SaveToSource() { }
	// RVA: 0x2fe04d4 VA: 0x75955f84d4
	public Void .ctor() { }
}
```