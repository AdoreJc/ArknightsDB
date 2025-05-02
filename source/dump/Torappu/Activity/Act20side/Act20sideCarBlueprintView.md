# Act20sideCarBlueprintView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `RectTransform _container`

- `UIAtlasImage _selectCircle`

- `Sequence m_sequence`

- `CartAccessoryPos m_cachePos`

- `UIAtlasObject m_atlasObject`


## Methods

- `UIAtlasObject _EnsureAtlasObject()`

- `Void OnDestroy()`

- `Void _UnloadCart()`

- `SpriteRenderData _GetSpriteCart(String, CartAccessoryPos)`

- `Void SetPos(String, CartAccessoryPos)`

- `Sequence _GetTweenSeq(Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarBlueprintView : MonoBehaviour, IHotfixable
{
	private List`1 posList; // 0x18
	private RectTransform _container; // 0x20
	private UIAtlasImage _selectCircle; // 0x28
	private Sequence m_sequence; // 0x30
	private CartAccessoryPos m_cachePos; // 0x38
	private UIAtlasObject m_atlasObject; // 0x40
	private static DelegateBridge __Hotfix0__EnsureAtlasObject; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__UnloadCart; // 0x10
	private static DelegateBridge __Hotfix0__GetSpriteCart; // 0x18
	private static DelegateBridge __Hotfix0_SetPos; // 0x20
	private static DelegateBridge __Hotfix0__GetTweenSeq; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32ed358 VA: 0x7595905358
	private UIAtlasObject _EnsureAtlasObject() { }
	// RVA: 0x32ed480 VA: 0x7595905480
	private Void OnDestroy() { }
	// RVA: 0x32ed4e8 VA: 0x75959054e8
	private Void _UnloadCart() { }
	// RVA: 0x32ed628 VA: 0x7595905628
	private SpriteRenderData _GetSpriteCart(String compId, CartAccessoryPos pos) { }
	// RVA: 0x32ed780 VA: 0x7595905780
	public Void SetPos(String selectId, CartAccessoryPos pos) { }
	// RVA: 0x32ed99c VA: 0x759590599c
	private Sequence _GetTweenSeq(Vector3 pos) { }
	// RVA: 0x32edc08 VA: 0x7595905c08
	public Void .ctor() { }
}
```