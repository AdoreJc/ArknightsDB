# UICharacterDynPortrait

**Namespace:** `Torappu.UI`


## Fields

- `SkeletonGraphic _graphic`


## Properties

- `SkeletonGraphic graphic`


## Methods

- `SkeletonGraphic get_graphic()`

- `Boolean _SetAnimation(String, Boolean)`

- `Boolean _AddAnimation(String, Boolean)`

- `Boolean _PlayAnimation(String, Boolean, Boolean, out)`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterDynPortrait : MonoBehaviour, IHotfixable
{
	public const String IDLE_ANIM; // 0x0
	private SkeletonGraphic _graphic; // 0x18
	private static DelegateBridge __Hotfix0_get_graphic; // 0x0
	private static DelegateBridge __Hotfix0__SetAnimation; // 0x8
	private static DelegateBridge __Hotfix0__AddAnimation; // 0x10
	private static DelegateBridge __Hotfix0__PlayAnimation; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public SkeletonGraphic graphic { get; }

	// RVA: 0x212df78 VA: 0x7594745f78
	public SkeletonGraphic get_graphic() { }
	// RVA: 0x212dfe0 VA: 0x7594745fe0
	private Boolean _SetAnimation(String animKey, Boolean loop) { }
	// RVA: 0x212e270 VA: 0x7594746270
	private Boolean _AddAnimation(String animKey, Boolean loop) { }
	// RVA: 0x212e080 VA: 0x7594746080
	private Boolean _PlayAnimation(String animKey, Boolean loop, Boolean isAdd, out Single time) { }
	// RVA: 0x212e310 VA: 0x7594746310
	private Void Start() { }
	// RVA: 0x212e3c0 VA: 0x75947463c0
	public Void .ctor() { }
}
```