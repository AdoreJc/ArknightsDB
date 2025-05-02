# ShopKeeperGraphic

**Namespace:** `Torappu.UI.Shop`


## Fields

- `SkeletonGraphic _graphic`

- `Options _options`

- `StateMachine m_stateMachine`


## Methods

- `Void OnInteract()`

- `Boolean _SetAnimation(String, Boolean)`

- `Boolean _AddAnimation(String, Boolean)`

- `Boolean _PlayAnimation(String, Boolean, Boolean, out)`

- `Void Start()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopKeeperGraphic : MonoBehaviour
{
	private SkeletonGraphic _graphic; // 0x18
	private Options _options; // 0x20
	private StateMachine m_stateMachine; // 0x28


	// RVA: 0x2466878 VA: 0x7594a7e878
	public Void OnInteract() { }
	// RVA: 0x24668b8 VA: 0x7594a7e8b8
	private Boolean _SetAnimation(String animKey, Boolean loop) { }
	// RVA: 0x2466a60 VA: 0x7594a7ea60
	private Boolean _AddAnimation(String animKey, Boolean loop) { }
	// RVA: 0x24668dc VA: 0x7594a7e8dc
	private Boolean _PlayAnimation(String animKey, Boolean loop, Boolean isAdd, out Single time) { }
	// RVA: 0x2466a84 VA: 0x7594a7ea84
	private Void Start() { }
	// RVA: 0x2466c1c VA: 0x7594a7ec1c
	private Void Update() { }
	// RVA: 0x2466ca4 VA: 0x7594a7eca4
	public Void .ctor() { }
}
```