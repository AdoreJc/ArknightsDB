# AVGCharacterSpriteHub

**Namespace:** `Torappu.AVG`


## Fields

- `Vector3 FacePos`

- `Vector2 FaceSize`

- `RectTransform m_rectTransform`


## Methods

- `Void SetImage(AlphaSplitImageHolder, Int32, Single, Single)`

- `Void SetImage(AlphaSplitImageHolder, String, Single, Single)`

- `Void _PickSetImageImpl(AlphaSplitImageHolder, SpriteConfig, Single, Single)`

- `Boolean _HasFace()`

- `Void _SetImage(AlphaSplitImageHolder, SpriteConfig, SpriteConfig, Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCharacterSpriteHub : MonoBehaviour, IHotfixable
{
	public SpriteConfig[] sprites; // 0x18
	public Vector3 FacePos; // 0x20
	public Vector2 FaceSize; // 0x2c
	private RectTransform m_rectTransform; // 0x38
	private static DelegateBridge __Hotfix0_SetImage; // 0x0
	private static DelegateBridge __Hotfix1_SetImage; // 0x8
	private static DelegateBridge __Hotfix0__PickSetImageImpl; // 0x10
	private static DelegateBridge __Hotfix0__HasFace; // 0x18
	private static DelegateBridge __Hotfix0__SetImage; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3e9dbf0 VA: 0x75964b5bf0
	public Void SetImage(AlphaSplitImageHolder imageHolder, Int32 index, Single blackStart, Single blackEnd) { }
	// RVA: 0x3e9d5c8 VA: 0x75964b55c8
	public Void SetImage(AlphaSplitImageHolder imageHolder, String alias, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea3fa8 VA: 0x75964bbfa8
	private Void _PickSetImageImpl(AlphaSplitImageHolder imageHolder, SpriteConfig targetConfig, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea4130 VA: 0x75964bc130
	private Boolean _HasFace() { }
	// RVA: 0x3ea4228 VA: 0x75964bc228
	private Void _SetImage(AlphaSplitImageHolder imageHolder, SpriteConfig config, SpriteConfig faceConfig, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea45f4 VA: 0x75964bc5f4
	public Void .ctor() { }
}
```