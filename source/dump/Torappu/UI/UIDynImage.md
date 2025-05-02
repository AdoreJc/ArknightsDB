# UIDynImage

**Namespace:** `Torappu.UI`


## Fields

- `Image m_image`

- `Sprite m_cachedSprite`

- `String m_cachedPath`


## Properties

- `Image target`


## Methods

- `Image get_target()`

- `Void SetImage(String, Boolean)`

- `Sprite _LoadSprite(String)`

- `Void _UnloadImageIfNot()`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIDynImage : MonoBehaviour, IHotfixable
{
	private Image m_image; // 0x18
	private Sprite m_cachedSprite; // 0x20
	private String m_cachedPath; // 0x28
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_SetImage; // 0x8
	private static DelegateBridge __Hotfix0__LoadSprite; // 0x10
	private static DelegateBridge __Hotfix0__UnloadImageIfNot; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Image target { get; }

	// RVA: 0x21d4444 VA: 0x75947ec444
	public Image get_target() { }
	// RVA: 0x21d44ac VA: 0x75947ec4ac
	public Void SetImage(String path, Boolean forceReload) { }
	// RVA: 0x21d488c VA: 0x75947ec88c
	private Sprite _LoadSprite(String path) { }
	// RVA: 0x21d46d0 VA: 0x75947ec6d0
	private Void _UnloadImageIfNot() { }
	// RVA: 0x21d49d0 VA: 0x75947ec9d0
	private Void Start() { }
	// RVA: 0x21d4ac4 VA: 0x75947ecac4
	private Void OnDestroy() { }
	// RVA: 0x21d4b2c VA: 0x75947ecb2c
	public Void .ctor() { }
}
```