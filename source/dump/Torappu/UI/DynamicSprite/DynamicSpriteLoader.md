# DynamicSpriteLoader

**Namespace:** `Torappu.UI.DynamicSprite`


## Fields

- `BakeInfo _bakeInfo`

- `ISpriteAssetLoader m_assetLoader`

- `Boolean m_isVisible`

- `Boolean m_isLoading`

- `Boolean m_isLoaded`


## Methods

- `Void NotifyLoaderReady(ISpriteAssetLoader)`

- `Void _LoadSpriteIfReady()`

- `Void OnPrefabUpdated()`

- `Void <_LoadSpriteIfReady>b__9_0(Sprite)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DynamicSprite
public class DynamicSpriteLoader : MonoBehaviour, IOnPrefabUpdated
{
	private BakeInfo _bakeInfo; // 0x18
	private ISpriteAssetLoader m_assetLoader; // 0x28
	private Boolean m_isVisible; // 0x30
	private Boolean m_isLoading; // 0x31
	private Boolean m_isLoaded; // 0x32


	// RVA: 0x2c46a3c VA: 0x759525ea3c
	protected virtual Void OnEnable() { }
	// RVA: 0x2c46b84 VA: 0x759525eb84
	protected virtual Void OnDisable() { }
	// RVA: 0x2c46214 VA: 0x759525e214
	public Void NotifyLoaderReady(ISpriteAssetLoader loader) { }
	// RVA: 0x2c46a48 VA: 0x759525ea48
	private Void _LoadSpriteIfReady() { }
	// RVA: 0x2c46b8c VA: 0x759525eb8c
	public Void OnPrefabUpdated() { }
	// RVA: 0x2c46b90 VA: 0x759525eb90
	public Void .ctor() { }
	// RVA: 0x2c46c04 VA: 0x759525ec04
	private Void <_LoadSpriteIfReady>b__9_0(Sprite sprite) { }
}
```