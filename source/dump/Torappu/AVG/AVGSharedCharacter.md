# AVGSharedCharacter

**Namespace:** `Torappu.AVG`


## Fields

- `Ease _fadeEade`

- `AlphaSplitImageHolder m_imageHolder`

- `Image m_charImage`

- `Object <cachedPrefab>k__BackingField`

- `String <currCharKey>k__BackingField`


## Properties

- `Object cachedPrefab`

- `String currCharKey`


## Methods

- `Object get_cachedPrefab()`

- `Void set_cachedPrefab(Object)`

- `String get_currCharKey()`

- `Void set_currCharKey(String)`

- `Void SetCharacter(Func`2, Option)`

- `Void _InitIfNot()`

- `Void _FadeOutOldCharAndSetChar(Func`2, Option)`

- `Void _SetImage(Func`2, Option)`

- `Boolean _LoadImage(Func`2, Option)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGSharedCharacter : MonoBehaviour, IHotfixable
{
	private const Char INDEX_TOKEN; // 0x0
	private const Char ALIAS_TOKEN; // 0x0
	private const Char BODY_TOKEN; // 0x0
	private Ease _fadeEade; // 0x18
	private AlphaSplitImageHolder m_imageHolder; // 0x20
	private Image m_charImage; // 0x28
	private Object <cachedPrefab>k__BackingField; // 0x30
	private String <currCharKey>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_cachedPrefab; // 0x0
	private static DelegateBridge __Hotfix0_set_cachedPrefab; // 0x8
	private static DelegateBridge __Hotfix0_get_currCharKey; // 0x10
	private static DelegateBridge __Hotfix0_set_currCharKey; // 0x18
	private static DelegateBridge __Hotfix0_SetCharacter; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__FadeOutOldCharAndSetChar; // 0x30
	private static DelegateBridge __Hotfix0__SetImage; // 0x38
	private static DelegateBridge __Hotfix0__LoadImage; // 0x40
	private static DelegateBridge __Hotfix0__TryParseBody; // 0x48
	private static DelegateBridge __Hotfix0__TryParseAlias; // 0x50
	private static DelegateBridge __Hotfix0__ParseIndex; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Object cachedPrefab { get; set; }
	public String currCharKey { get; set; }

	// RVA: 0x3e9c7b4 VA: 0x75964b47b4
	public Object get_cachedPrefab() { }
	// RVA: 0x3e9c81c VA: 0x75964b481c
	private Void set_cachedPrefab(Object value) { }
	// RVA: 0x3e9c8a0 VA: 0x75964b48a0
	public String get_currCharKey() { }
	// RVA: 0x3e9c908 VA: 0x75964b4908
	private Void set_currCharKey(String value) { }
	// RVA: 0x3e9c98c VA: 0x75964b498c
	public Void SetCharacter(Func`2 loadFunc, Option option) { }
	// RVA: 0x3e9cb10 VA: 0x75964b4b10
	private Void _InitIfNot() { }
	// RVA: 0x3e9ce00 VA: 0x75964b4e00
	private Void _FadeOutOldCharAndSetChar(Func`2 loadFunc, Option option) { }
	// RVA: 0x3e9ccb8 VA: 0x75964b4cb8
	private Void _SetImage(Func`2 loadFunc, Option option) { }
	// RVA: 0x3e9cfd8 VA: 0x75964b4fd8
	private Boolean _LoadImage(Func`2 loadFunc, Option option) { }
	// RVA: 0x3e9d3a4 VA: 0x75964b53a4
	private static Boolean _TryParseBody(ref String key, out Int32 body) { }
	// RVA: 0x3e9d4b8 VA: 0x75964b54b8
	private static Boolean _TryParseAlias(ref String key, out String alias) { }
	// RVA: 0x3e9dae8 VA: 0x75964b5ae8
	private static Void _ParseIndex(ref String key, out Int32 index) { }
	// RVA: 0x3e9e198 VA: 0x75964b6198
	public Void .ctor() { }
}
```