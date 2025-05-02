# UIUniWebViewInstCenter

**Namespace:** `Torappu.UI`


## Fields

- `Transform _instHolder`


## Methods

- `Void _AdjustWebViews()`

- `WebViewHolder _EnsureHolder(UIUniWebView)`

- `UniWebView _CreateInst()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIUniWebViewInstCenter : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IHotfixable
{
	private Transform _instHolder; // 0x18
	private List`1 m_webViews; // 0x20
	private static DelegateBridge __Hotfix0_AchieveWebView; // 0x0
	private static DelegateBridge __Hotfix0_MarkDestroy; // 0x8
	private static DelegateBridge __Hotfix0__AdjustWebViews; // 0x10
	private static DelegateBridge __Hotfix0__EnsureHolder; // 0x18
	private static DelegateBridge __Hotfix0__CreateInst; // 0x20
	private static DelegateBridge __Hotfix0__DestroyWebView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2203918 VA: 0x759481b918
	public static UniWebView AchieveWebView(UIUniWebView key) { }
	// RVA: 0x2203a54 VA: 0x759481ba54
	public static Void MarkDestroy(UIUniWebView key) { }
	// RVA: 0x2203ed4 VA: 0x759481bed4
	private Void _AdjustWebViews() { }
	// RVA: 0x2204018 VA: 0x759481c018
	private WebViewHolder _EnsureHolder(UIUniWebView key) { }
	// RVA: 0x220427c VA: 0x759481c27c
	private UniWebView _CreateInst() { }
	// RVA: 0x220446c VA: 0x759481c46c
	private static Void _DestroyWebView(UniWebView webView) { }
	// RVA: 0x2204588 VA: 0x759481c588
	public Void .ctor() { }
}
```