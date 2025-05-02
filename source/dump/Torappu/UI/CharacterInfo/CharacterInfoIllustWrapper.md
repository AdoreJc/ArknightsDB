# CharacterInfoIllustWrapper

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _scaleIllustration`

- `UICharacterIllust m_illust`

- `RectTransform m_rectTransform`

- `Single m_scale`

- `Boolean m_cacheForceStatic`

- `Vector2 m_initScale`

- `Vector2 m_initPosition`

- `IllustCache m_illustCache`


## Properties

- `Single scale`

- `UICharacterIllust illust`

- `RectTransform rectTransform`


## Methods

- `Void Awake()`

- `Void ResetContent(CharacterIllustViewModel, UICharacterIllustLoader, Boolean)`

- `Void ResetContent(CharUISkinStruct, UICharacterIllustLoader, Boolean)`

- `Void ResetContentSkinShopOnly(CharUISkinStruct, UICharacterIllustLoader)`

- `Single get_scale()`

- `Void set_scale(Single)`

- `UICharacterIllust get_illust()`

- `RectTransform get_rectTransform()`

- `Void _ResetContent(CharUISkinStruct, UICharacterIllustLoader, Boolean)`

- `Void _ResetContent(String, UICharacterIllustLoader, IllustNPCResType, CharUISkinStruct)`

- `Void _ResetContentShopOnly(CharUISkinStruct, UICharacterIllustLoader)`

- `Void _ResetContentInternal(Func`1)`

- `Void _UpdateScale()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoIllustWrapper : MonoBehaviour, IHotfixable
{
	private Single _scaleIllustration; // 0x18
	private UICharacterIllust m_illust; // 0x20
	private RectTransform m_rectTransform; // 0x28
	private Single m_scale; // 0x30
	private Boolean m_cacheForceStatic; // 0x34
	private Vector2 m_initScale; // 0x38
	private Vector2 m_initPosition; // 0x40
	private IllustCache m_illustCache; // 0x48
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_ResetContent; // 0x8
	private static DelegateBridge __Hotfix1_ResetContent; // 0x10
	private static DelegateBridge __Hotfix0_ResetContentSkinShopOnly; // 0x18
	private static DelegateBridge __Hotfix0_get_scale; // 0x20
	private static DelegateBridge __Hotfix0_set_scale; // 0x28
	private static DelegateBridge __Hotfix0_get_illust; // 0x30
	private static DelegateBridge __Hotfix0_get_rectTransform; // 0x38
	private static DelegateBridge __Hotfix0__ResetContent; // 0x40
	private static DelegateBridge __Hotfix1__ResetContent; // 0x48
	private static DelegateBridge __Hotfix0__ResetContentShopOnly; // 0x50
	private static DelegateBridge __Hotfix0__ResetContentInternal; // 0x58
	private static DelegateBridge __Hotfix0__UpdateScale; // 0x60
	private static DelegateBridge __Hotfix0__IllustLoaderFromPage; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Single scale { get; set; }
	public UICharacterIllust illust { get; }
	public RectTransform rectTransform { get; }

	// RVA: 0x2d734a4 VA: 0x759538b4a4
	private Void Awake() { }
	// RVA: 0x2d71534 VA: 0x7595389534
	public Void ResetContent(CharacterIllustViewModel viewModel, UICharacterIllustLoader loader, Boolean forceStatic) { }
	// RVA: 0x2d73aa8 VA: 0x759538baa8
	public Void ResetContent(CharUISkinStruct skin, UICharacterIllustLoader loader, Boolean forceStatic) { }
	// RVA: 0x2d73b58 VA: 0x759538bb58
	public Void ResetContentSkinShopOnly(CharUISkinStruct skin, UICharacterIllustLoader loader) { }
	// RVA: 0x2d73e28 VA: 0x759538be28
	public Single get_scale() { }
	// RVA: 0x2d727c8 VA: 0x759538a7c8
	public Void set_scale(Single value) { }
	// RVA: 0x2d71148 VA: 0x7595389148
	public UICharacterIllust get_illust() { }
	// RVA: 0x2d730e0 VA: 0x759538b0e0
	public RectTransform get_rectTransform() { }
	// RVA: 0x2d7382c VA: 0x759538b82c
	private Void _ResetContent(CharUISkinStruct skin, UICharacterIllustLoader loader, Boolean forceStatic) { }
	// RVA: 0x2d73620 VA: 0x759538b620
	private Void _ResetContent(String npcId, UICharacterIllustLoader loader, IllustNPCResType resFolder, CharUISkinStruct npcIllust) { }
	// RVA: 0x2d73bfc VA: 0x759538bbfc
	private Void _ResetContentShopOnly(CharUISkinStruct skin, UICharacterIllustLoader loader) { }
	// RVA: 0x2d73f58 VA: 0x759538bf58
	private Void _ResetContentInternal(Func`1 loadIllustFunc) { }
	// RVA: 0x2d73514 VA: 0x759538b514
	private Void _UpdateScale() { }
	// RVA: 0x2d741d0 VA: 0x759538c1d0
	private static UICharacterIllustLoader _IllustLoaderFromPage(UICharacterIllustLoader loader) { }
	// RVA: 0x2d74298 VA: 0x759538c298
	public Void .ctor() { }
}
```