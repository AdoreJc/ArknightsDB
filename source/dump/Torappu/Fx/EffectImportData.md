# EffectImportData

**Namespace:** `Torappu.Fx`


## Fields

- `String _importName`

- `String _resourceName`

- `SortingLayerWrapper _sortingLayerId`

- `Boolean _removeTopAnimator`

- `Boolean _convertFxDelayToDelayToStart`

- `Boolean _isUIEffect`


## Properties

- `Boolean removeTopAnimator`

- `Boolean isUIEffect`

- `Boolean convertFxDelayToDelayToStart`


## Methods

- `Boolean get_removeTopAnimator()`

- `Boolean get_isUIEffect()`

- `Boolean get_convertFxDelayToDelayToStart()`

- `String GetImportName()`

- `String GetResourceName()`

- `Int32 GetSortingLayerID()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class EffectImportData : MonoBehaviour
{
	private String _importName; // 0x18
	private String _resourceName; // 0x20
	private SortingLayerWrapper _sortingLayerId; // 0x28
	private Boolean _removeTopAnimator; // 0x2c
	private Boolean _convertFxDelayToDelayToStart; // 0x2d
	private Boolean _isUIEffect; // 0x2e

	public Boolean removeTopAnimator { get; }
	public Boolean isUIEffect { get; }
	public Boolean convertFxDelayToDelayToStart { get; }

	// RVA: 0x3f00bc8 VA: 0x7596518bc8
	public Boolean get_removeTopAnimator() { }
	// RVA: 0x3f00bd0 VA: 0x7596518bd0
	public Boolean get_isUIEffect() { }
	// RVA: 0x3f00bd8 VA: 0x7596518bd8
	public Boolean get_convertFxDelayToDelayToStart() { }
	// RVA: 0x3f00be0 VA: 0x7596518be0
	public String GetImportName() { }
	// RVA: 0x3f00c14 VA: 0x7596518c14
	public String GetResourceName() { }
	// RVA: 0x3f00c48 VA: 0x7596518c48
	public Int32 GetSortingLayerID() { }
	// RVA: 0x3f00c50 VA: 0x7596518c50
	public Void .ctor() { }
}
```