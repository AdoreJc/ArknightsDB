# ActivityGameObjectAssetHolder

**Namespace:** `Torappu.Activity`


## Methods

- `Boolean TryFindGameObject(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityGameObjectAssetHolder : ActivityAssetHolder
{
	private GameObject[] _gameObjectList; // 0x28
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x0
	private static DelegateBridge __Hotfix0_TryFindGameObject; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30bfe24 VA: 0x75956d7e24
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c003c VA: 0x75956d803c
	public Boolean TryFindGameObject(String id, out GameObject gameObject) { }
	// RVA: 0x30c0198 VA: 0x75956d8198
	public Void .ctor() { }
}
```