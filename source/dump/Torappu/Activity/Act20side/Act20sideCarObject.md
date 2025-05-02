# Act20sideCarObject

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `UIAtlasImage _roofImg`

- `UIAtlasImage _headStockImg`

- `UIAtlasImage _trunk1`

- `UIAtlasImage _trunk2`

- `Image _carFrame`

- `String m_cacheFrameId`

- `UIAtlasObject m_atlasObject`


## Methods

- `UIAtlasObject _EnsureAtlasObject()`

- `Void OnDestroy()`

- `Void _UnloadCart()`

- `SpriteRenderData _GetSpriteCart(String, CartAccessoryPos)`

- `Void RenderCart(Dictionary`2, String)`

- `Void RenderCart(Cart, String)`

- `Void _RenderCart(Dictionary`2, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarObject : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _roofImg; // 0x18
	private UIAtlasImage _headStockImg; // 0x20
	private UIAtlasImage _trunk1; // 0x28
	private UIAtlasImage _trunk2; // 0x30
	private Image _carFrame; // 0x38
	private String m_cacheFrameId; // 0x40
	private UIAtlasObject m_atlasObject; // 0x48
	private static DelegateBridge __Hotfix0__EnsureAtlasObject; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__UnloadCart; // 0x10
	private static DelegateBridge __Hotfix0__GetSpriteCart; // 0x18
	private static DelegateBridge __Hotfix0_RenderCart; // 0x20
	private static DelegateBridge __Hotfix1_RenderCart; // 0x28
	private static DelegateBridge __Hotfix0__RenderCart; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x32ec11c VA: 0x759590411c
	private UIAtlasObject _EnsureAtlasObject() { }
	// RVA: 0x32ec244 VA: 0x7595904244
	private Void OnDestroy() { }
	// RVA: 0x32ec2ac VA: 0x75959042ac
	private Void _UnloadCart() { }
	// RVA: 0x32ec3ec VA: 0x75959043ec
	private SpriteRenderData _GetSpriteCart(String compId, CartAccessoryPos pos) { }
	// RVA: 0x32ec544 VA: 0x7595904544
	public Void RenderCart(Dictionary`2 cartDetail, String pageName) { }
	// RVA: 0x32ecb2c VA: 0x7595904b2c
	public Void RenderCart(Cart car, String pageName) { }
	// RVA: 0x32ec758 VA: 0x7595904758
	private Void _RenderCart(Dictionary`2 car, String pageName) { }
	// RVA: 0x32ecbb8 VA: 0x7595904bb8
	public Void .ctor() { }
}
```