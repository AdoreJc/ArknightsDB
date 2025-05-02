# AVGCharacterSlot

**Namespace:** `Torappu.AVG`


## Fields

- `Image _foreImage`

- `Image _backImage`

- `RectTransform _offset`

- `RectTransform _shakeContainer`

- `Ease _fadeEase`

- `String m_currentKey`

- `Single m_currBlackStart`

- `Single m_currBlackEnd`

- `String m_currentFaceKey`

- `AlphaSplitImageHolder m_foreImageHolder`

- `AlphaSplitImageHolder m_backImageHolder`


## Properties

- `Image currentImage`


## Methods

- `Image get_currentImage()`

- `Void Set(String, Single, Color)`

- `Void Set(String, Single, Color, Boolean, Boolean, Single, Single, ECharTransType)`

- `Void Clear(Single)`

- `Void ClearSelfAndImageHolders()`

- `Void OnReset()`

- `Void SetFocus(Boolean, Boolean)`

- `Void BindPostDisplay(String, String, AVGCompBridge)`

- `Tween MoveChar(Single, Single, Single)`

- `Tween CharJump(Single, Single, Single, Int32, Single)`

- `Tween CharShake(Single, Int32, Single, Int32)`

- `Tween CharZoom(Single, Single, Single, Single)`

- `Tween SetCharPos(Single, Single, Single)`

- `Tween _GenForeImageTween(Color, Single)`

- `Tween _GenBackImageTween(Single)`

- `Single _GenOriginAlphaWithTransType(ECharTransType)`

- `Void Awake()`

- `Void _InitImageHolders()`

- `Void _ResetLocationAndTween()`

- `Tween SlotChangeChar(String, Single, Color, Single, Single, Single, Single)`

- `Tween SlotMoveChar(Vector2, Vector2, Single)`

- `Tween SlotSetChar(String, Single, Color, Single, Single, Single, Single, Boolean)`

- `Tween SlotChangeAlpha(Single, Single, Single)`

- `Tween SlotCleanChar(Single)`

- `Sequence SlotChangeMask(Single, Single, Single)`

- `Void <_GenBackImageTween>b__32_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCharacterSlot : MonoBehaviour, IHotfixable
{
	public const Char INDEX_TOKEN; // 0x0
	public const Char ALIAS_TOKEN; // 0x0
	public const Char BODY_TOKEN; // 0x0
	public const String EMPTY_CHARACTER; // 0x0
	private const Single ALPHA_ZERO; // 0x0
	private const Single ALPHA_ONE; // 0x0
	private Image _foreImage; // 0x18
	private Image _backImage; // 0x20
	private RectTransform _offset; // 0x28
	private RectTransform _shakeContainer; // 0x30
	private Ease _fadeEase; // 0x38
	private String m_currentKey; // 0x40
	private Single m_currBlackStart; // 0x48
	private Single m_currBlackEnd; // 0x4c
	private String m_currentFaceKey; // 0x50
	private AlphaSplitImageHolder m_foreImageHolder; // 0x58
	private AlphaSplitImageHolder m_backImageHolder; // 0x60
	private static DelegateBridge __Hotfix0_get_currentImage; // 0x0
	private static DelegateBridge __Hotfix0_Set; // 0x8
	private static DelegateBridge __Hotfix1_Set; // 0x10
	private static DelegateBridge __Hotfix0_Clear; // 0x18
	private static DelegateBridge __Hotfix0_ClearSelfAndImageHolders; // 0x20
	private static DelegateBridge __Hotfix0_OnReset; // 0x28
	private static DelegateBridge __Hotfix0_SetFocus; // 0x30
	private static DelegateBridge __Hotfix0_BindPostDisplay; // 0x38
	private static DelegateBridge __Hotfix0_MoveChar; // 0x40
	private static DelegateBridge __Hotfix0_CharJump; // 0x48
	private static DelegateBridge __Hotfix0_CharShake; // 0x50
	private static DelegateBridge __Hotfix0_CharZoom; // 0x58
	private static DelegateBridge __Hotfix0_SetCharPos; // 0x60
	private static DelegateBridge __Hotfix0__GenForeImageTween; // 0x68
	private static DelegateBridge __Hotfix0__GenBackImageTween; // 0x70
	private static DelegateBridge __Hotfix0__GenOriginAlphaWithTransType; // 0x78
	private static DelegateBridge __Hotfix0__LoadImage; // 0x80
	private static DelegateBridge __Hotfix0__SwapImages; // 0x88
	private static DelegateBridge __Hotfix0__TryParseAlias; // 0x90
	private static DelegateBridge __Hotfix0__TryParseIndex; // 0x98
	private static DelegateBridge __Hotfix0__TryParseBody; // 0xa0
	private static DelegateBridge __Hotfix0__GetIdWithoutAliasOrIndex; // 0xa8
	private static DelegateBridge __Hotfix0_Awake; // 0xb0
	private static DelegateBridge __Hotfix0__InitImageHolders; // 0xb8
	private static DelegateBridge __Hotfix0__ResetLocationAndTween; // 0xc0
	private static DelegateBridge __Hotfix0_SlotChangeChar; // 0xc8
	private static DelegateBridge __Hotfix0_SlotMoveChar; // 0xd0
	private static DelegateBridge __Hotfix0_SlotSetChar; // 0xd8
	private static DelegateBridge __Hotfix0_SlotChangeAlpha; // 0xe0
	private static DelegateBridge __Hotfix0_SlotCleanChar; // 0xe8
	private static DelegateBridge __Hotfix0_SlotChangeMask; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8

	public Image currentImage { get; }

	// RVA: 0x3ea13b8 VA: 0x75964b93b8
	public Image get_currentImage() { }
	// RVA: 0x3ea0398 VA: 0x75964b8398
	public Void Set(String key, Single duration, Color color) { }
	// RVA: 0x3ea1420 VA: 0x75964b9420
	public Void Set(String key, Single duration, Color color, Boolean dontFadeIfSameChar, Boolean resetOffsetPos, Single blackStart, Single blackEnd, ECharTransType transType) { }
	// RVA: 0x3ea0cb8 VA: 0x75964b8cb8
	public Void Clear(Single duration) { }
	// RVA: 0x3ea233c VA: 0x75964ba33c
	public Void ClearSelfAndImageHolders() { }
	// RVA: 0x3ea24f4 VA: 0x75964ba4f4
	public Void OnReset() { }
	// RVA: 0x3ea258c VA: 0x75964ba58c
	public Void SetFocus(Boolean isFocus, Boolean forceSibling) { }
	// RVA: 0x3ea2674 VA: 0x75964ba674
	public Void BindPostDisplay(String foreChannel, String backChannel, AVGCompBridge bridge) { }
	// RVA: 0x3ea2878 VA: 0x75964ba878
	public Tween MoveChar(Single x, Single y, Single fadeTime) { }
	// RVA: 0x3ea29e0 VA: 0x75964ba9e0
	public Tween CharJump(Single x, Single y, Single jumpPower, Int32 times, Single fadeTime) { }
	// RVA: 0x3ea2b0c VA: 0x75964bab0c
	public Tween CharShake(Single shakePower, Int32 times, Single fadeTime, Int32 random) { }
	// RVA: 0x3ea2c58 VA: 0x75964bac58
	public Tween CharZoom(Single xPos, Single yPos, Single scale, Single fadeTime) { }
	// RVA: 0x3ea2ef4 VA: 0x75964baef4
	public Tween SetCharPos(Single x, Single y, Single fadeTime) { }
	// RVA: 0x3ea2088 VA: 0x75964ba088
	private Tween _GenForeImageTween(Color color, Single duration) { }
	// RVA: 0x3ea21c0 VA: 0x75964ba1c0
	private Tween _GenBackImageTween(Single duration) { }
	// RVA: 0x3ea2000 VA: 0x75964ba000
	private Single _GenOriginAlphaWithTransType(ECharTransType transType) { }
	// RVA: 0x3ea19dc VA: 0x75964b99dc
	private static Boolean _LoadImage(AlphaSplitImageHolder imageHolder, String key, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea18c8 VA: 0x75964b98c8
	private static Void _SwapImages(ref Image lhs, ref Image rhs, ref AlphaSplitImageHolder lhsHolder, ref AlphaSplitImageHolder rhsHolder) { }
	// RVA: 0x3ea3160 VA: 0x75964bb160
	private static Boolean _TryParseAlias(ref String key, out String alias) { }
	// RVA: 0x3ea3260 VA: 0x75964bb260
	private static Boolean _TryParseIndex(ref String key, out Int32 index) { }
	// RVA: 0x3ea305c VA: 0x75964bb05c
	private static Boolean _TryParseBody(ref String key, out Int32 body) { }
	// RVA: 0x3ea1818 VA: 0x75964b9818
	private static String _GetIdWithoutAliasOrIndex(String key) { }
	// RVA: 0x3ea3360 VA: 0x75964bb360
	private Void Awake() { }
	// RVA: 0x3ea2738 VA: 0x75964ba738
	private Void _InitImageHolders() { }
	// RVA: 0x3ea23d4 VA: 0x75964ba3d4
	private Void _ResetLocationAndTween() { }
	// RVA: 0x3ea33c8 VA: 0x75964bb3c8
	public Tween SlotChangeChar(String charName, Single duration, Color color, Single aFrom, Single aTo, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea3768 VA: 0x75964bb768
	public Tween SlotMoveChar(Vector2 posFrom, Vector2 posTo, Single duration) { }
	// RVA: 0x3ea34c8 VA: 0x75964bb4c8
	public Tween SlotSetChar(String charName, Single duration, Color color, Single aFrom, Single aTo, Single blackStart, Single blackEnd, Boolean resetOffsetPos) { }
	// RVA: 0x3ea3904 VA: 0x75964bb904
	public Tween SlotChangeAlpha(Single aFrom, Single aTo, Single duration) { }
	// RVA: 0x3ea3a74 VA: 0x75964bba74
	public Tween SlotCleanChar(Single duration) { }
	// RVA: 0x3ea3b68 VA: 0x75964bbb68
	public Sequence SlotChangeMask(Single bsTarget, Single beTarget, Single duration) { }
	// RVA: 0x3ea3e34 VA: 0x75964bbe34
	public Void .ctor() { }
	// RVA: 0x3ea3eac VA: 0x75964bbeac
	private Void <_GenBackImageTween>b__32_0() { }
}
```