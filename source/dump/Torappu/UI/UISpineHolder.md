# UISpineHolder

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _enableReverseMode`

- `UIStencilMaskable _stencilCleaner`

- `Material m_material`

- `SpineAsset m_asset`

- `Adapter m_adapter`

- `SkeletonGraphic m_graphic`

- `IEnumerator m_loadCoroutine`

- `Boolean m_isFadingOut`

- `Boolean m_animEnableReverse`


## Methods

- `SkeletonAnimation _LoadBattleSpine(String, out, out)`

- `SkeletonAnimation _LoadBuildingSpine(String, out, out)`

- `Void Init(Adapter)`

- `Boolean _RenderByAdapter(Adapter)`

- `Void _ApplyTransform(TRS, Single)`

- `IEnumerator _LoadSpineGraphic(SkeletonAnimation, SpineAnimParam)`

- `Void _UpdateSpineAnimParam(SkeletonGraphic, SpineAnimParam)`

- `Void _ReleaseIfNot()`

- `Void _EnableReverseMode()`

- `Void _DisableReverseMode()`

- `Void _ReverseMeshOrder(Boolean)`

- `Void Update()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISpineHolder : MonoBehaviour, IHotfixable
{
	private const Int32 REVERSE_MODE; // 0x0
	private const Single DEFAULT_FADEOUT_ALPHA; // 0x0
	private Boolean _enableReverseMode; // 0x18
	private UIStencilMaskable _stencilCleaner; // 0x20
	private Material m_material; // 0x28
	private SpineAsset m_asset; // 0x30
	private Adapter m_adapter; // 0x58
	private SkeletonGraphic m_graphic; // 0x60
	private IEnumerator m_loadCoroutine; // 0x68
	private Boolean m_isFadingOut; // 0x70
	private Boolean m_animEnableReverse; // 0x71
	private static DelegateBridge __Hotfix0__LoadBattleSpine; // 0x0
	private static DelegateBridge __Hotfix0__LoadBuildingSpine; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0__RenderByAdapter; // 0x18
	private static DelegateBridge __Hotfix0__ApplyTransform; // 0x20
	private static DelegateBridge __Hotfix0__LoadSpineGraphic; // 0x28
	private static DelegateBridge __Hotfix0__UpdateSpineAnimParam; // 0x30
	private static DelegateBridge __Hotfix0__ReleaseIfNot; // 0x38
	private static DelegateBridge __Hotfix0__EnableReverseMode; // 0x40
	private static DelegateBridge __Hotfix0__DisableReverseMode; // 0x48
	private static DelegateBridge __Hotfix0__ReverseMeshOrder; // 0x50
	private static DelegateBridge __Hotfix0_Update; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x21f0e44 VA: 0x7594808e44
	private SkeletonAnimation _LoadBattleSpine(String skinId, out Object asset, out Single spineScale) { }
	// RVA: 0x21f12e0 VA: 0x75948092e0
	private SkeletonAnimation _LoadBuildingSpine(String skinId, out Object asset, out Single spineScale) { }
	// RVA: 0x21f15c8 VA: 0x75948095c8
	public Void Init(Adapter adapter) { }
	// RVA: 0x21f17c0 VA: 0x75948097c0
	private Boolean _RenderByAdapter(Adapter adapter) { }
	// RVA: 0x21f20f4 VA: 0x759480a0f4
	private Void _ApplyTransform(TRS transformParam, Single spineScale) { }
	// RVA: 0x21f22f0 VA: 0x759480a2f0
	private IEnumerator _LoadSpineGraphic(SkeletonAnimation skeletonAnimation, SpineAnimParam animParam) { }
	// RVA: 0x21f23fc VA: 0x759480a3fc
	private Void _UpdateSpineAnimParam(SkeletonGraphic graphic, SpineAnimParam animParam) { }
	// RVA: 0x21f1b28 VA: 0x7594809b28
	private Void _ReleaseIfNot() { }
	// RVA: 0x21f285c VA: 0x759480a85c
	private Void _EnableReverseMode() { }
	// RVA: 0x21f2a94 VA: 0x759480aa94
	private Void _DisableReverseMode() { }
	// RVA: 0x21f2a00 VA: 0x759480aa00
	private Void _ReverseMeshOrder(Boolean reverseMesh) { }
	// RVA: 0x21f2c38 VA: 0x759480ac38
	private Void Update() { }
	// RVA: 0x21f2da8 VA: 0x759480ada8
	private Void OnDestroy() { }
	// RVA: 0x21f2e10 VA: 0x759480ae10
	public Void .ctor() { }
}
```