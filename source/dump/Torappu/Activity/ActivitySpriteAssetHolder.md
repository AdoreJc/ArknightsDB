# ActivitySpriteAssetHolder

**Namespace:** `Torappu.Activity`


## Methods

- `Boolean TryFindSprite(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivitySpriteAssetHolder : ActivityAssetHolder
{
	private Sprite[] _sprites; // 0x28
	private static DelegateBridge __Hotfix0_GetAssetIdList; // 0x0
	private static DelegateBridge __Hotfix0_TryFindSprite; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30c1768 VA: 0x75956d9768
	public override String[] GetAssetIdList() { }
	// RVA: 0x30c1980 VA: 0x75956d9980
	public Boolean TryFindSprite(String id, out Sprite sprite) { }
	// RVA: 0x30c1adc VA: 0x75956d9adc
	public Void .ctor() { }
}
```