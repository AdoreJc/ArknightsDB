# CutinTemplateDecoView

**Namespace:** `Torappu.UI`


## Fields

- `Text _text`

- `TwoStateToggle _toggle`

- `CanvasGroup _canvasGroup`

- `Tween m_cachedTw`

- `String m_cachedName`


## Methods

- `Void Render(DataBundle)`

- `Void Hide(Action)`

- `Void OnDestroy()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CutinTemplateDecoView : MonoBehaviour, IHotfixable
{
	private Text _text; // 0x18
	private TwoStateToggle _toggle; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private const Single ALPHA_ZERO; // 0x0
	private const Single HIDE_DURATION; // 0x0
	private Tween m_cachedTw; // 0x30
	private String m_cachedName; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x216ea5c VA: 0x7594786a5c
	public Void Render(DataBundle data) { }
	// RVA: 0x216f21c VA: 0x759478721c
	public Void Hide(Action callback) { }
	// RVA: 0x216f664 VA: 0x7594787664
	public Void OnDestroy() { }
	// RVA: 0x216f6e4 VA: 0x75947876e4
	public Void OnDisable() { }
	// RVA: 0x216f764 VA: 0x7594787764
	public Void .ctor() { }
}
```