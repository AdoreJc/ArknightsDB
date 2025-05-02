# UICommentedText

**Namespace:** `Torappu.UI`


## Fields

- `UICommentedTextDataBundle m_cachedDataBundle`

- `Boolean m_dirty`

- `String m_lastText`

- `Int32 m_lastSize`

- `UICommentedTextButton m_prefab`

- `Boolean m_useDarkColor`

- `UICommentedTextData m_cachedClickableTextData`


## Properties

- `Boolean useDarkColor`


## Methods

- `Boolean get_useDarkColor()`

- `Void set_useDarkColor(Boolean)`

- `Void SetClickableRichTextFromData(String)`

- `Void _PopulateMeshImpl(VertexHelper)`

- `Boolean _IsTempVertexValid()`

- `Void _CalculateClickableTextBound(UICommentedTextData, ref, ref, ref, Single, Single, Int32)`

- `Vector4 _GetCharBound()`

- `Void Update()`

- `Void _CreateTag()`

- `UICommentedTextButton _TryGetBtnFromPool()`

- `Void _PoolBtns()`

- `Void _LoadPrefabIfNeeded()`

- `Void _CreateClickableLink(UICommentedTextData)`

- `Void _OnTextClickEvent(UITermDescDataModel)`

- `Void <>xLuaBaseProxy_set_text(String)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommentedText : Text, IHotfixable
{
	private UICommentedTextDataBundle m_cachedDataBundle; // 0x148
	private List`1 m_showTextButtonList; // 0x150
	private List`1 m_textButtonPool; // 0x158
	private Dictionary`2 m_tagDict; // 0x160
	private Boolean m_dirty; // 0x168
	private String m_lastText; // 0x170
	private Int32 m_lastSize; // 0x178
	private UICommentedTextButton m_prefab; // 0x180
	private Boolean m_useDarkColor; // 0x188
	private const Single HOT_ZONE_SIZE_MULTIFILER; // 0x0
	private readonly UIVertex[] m_tempVerts; // 0x190
	private UICommentedTextData m_cachedClickableTextData; // 0x198
	private static DelegateBridge __Hotfix0_get_useDarkColor; // 0x0
	private static DelegateBridge __Hotfix0_set_useDarkColor; // 0x8
	private static DelegateBridge __Hotfix0_set_text; // 0x10
	private static DelegateBridge __Hotfix0_SetClickableRichTextFromData; // 0x18
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x20
	private static DelegateBridge __Hotfix0__PopulateMeshImpl; // 0x28
	private static DelegateBridge __Hotfix0__IsTempVertexValid; // 0x30
	private static DelegateBridge __Hotfix0__CalculateClickableTextBound; // 0x38
	private static DelegateBridge __Hotfix0__GetCharBound; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0__CreateTag; // 0x50
	private static DelegateBridge __Hotfix0__TryGetBtnFromPool; // 0x58
	private static DelegateBridge __Hotfix0__PoolBtns; // 0x60
	private static DelegateBridge __Hotfix0__LoadPrefabIfNeeded; // 0x68
	private static DelegateBridge __Hotfix0__CreateClickableLink; // 0x70
	private static DelegateBridge __Hotfix0__OnTextClickEvent; // 0x78
	private static DelegateBridge __Hotfix0_SetCommentedText; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Boolean useDarkColor { get; set; }
	public override String text { set; }

	// RVA: 0x22439f0 VA: 0x759485b9f0
	public Boolean get_useDarkColor() { }
	// RVA: 0x2243a58 VA: 0x759485ba58
	public Void set_useDarkColor(Boolean value) { }
	// RVA: 0x2243ad8 VA: 0x759485bad8
	public override Void set_text(String value) { }
	// RVA: 0x2243b58 VA: 0x759485bb58
	public Void SetClickableRichTextFromData(String rawRichText) { }
	// RVA: 0x2243d44 VA: 0x759485bd44
	protected override Void OnPopulateMesh(VertexHelper toFill) { }
	// RVA: 0x2243e80 VA: 0x759485be80
	private Void _PopulateMeshImpl(VertexHelper toFill) { }
	// RVA: 0x22449d0 VA: 0x759485c9d0
	private Boolean _IsTempVertexValid() { }
	// RVA: 0x22446e4 VA: 0x759485c6e4
	private Void _CalculateClickableTextBound(UICommentedTextData clickableTextData, ref Vector4 buttonBound, ref Boolean buttonBoundInit, ref Single lastCharMinY, Single xOffset, Single yOffset, Int32 stringIndex) { }
	// RVA: 0x2244a80 VA: 0x759485ca80
	protected Vector4 _GetCharBound() { }
	// RVA: 0x2244c90 VA: 0x759485cc90
	private Void Update() { }
	// RVA: 0x2244fe0 VA: 0x759485cfe0
	private Void _CreateTag() { }
	// RVA: 0x224545c VA: 0x759485d45c
	private UICommentedTextButton _TryGetBtnFromPool() { }
	// RVA: 0x2244db4 VA: 0x759485cdb4
	private Void _PoolBtns() { }
	// RVA: 0x224560c VA: 0x759485d60c
	private Void _LoadPrefabIfNeeded() { }
	// RVA: 0x2245178 VA: 0x759485d178
	private Void _CreateClickableLink(UICommentedTextData tagData) { }
	// RVA: 0x2245b60 VA: 0x759485db60
	private Void _OnTextClickEvent(UITermDescDataModel valuePair) { }
	// RVA: 0x2245c10 VA: 0x759485dc10
	public static Boolean SetCommentedText(Text text, String content, Boolean useDarkColor) { }
	// RVA: 0x2245d34 VA: 0x759485dd34
	public Void .ctor() { }
	// RVA: 0x2245e68 VA: 0x759485de68
	private Void <>xLuaBaseProxy_set_text(String P0) { }
	// RVA: 0x2245e70 VA: 0x759485de70
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```