# TuningProductFragSelectView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `CanvasGroup _clearBtnGroup`

- `Single _nonSelectAlpha`

- `Single _haveSelectAlpha`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(TuningProductViewModel)`

- `Void _RenderFragList(ListDict`2)`

- `Void ClearAllFrag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductFragSelectView : MonoBehaviour, IHotfixable
{
	private List`1 _fragList; // 0x18
	private CanvasGroup _clearBtnGroup; // 0x20
	private Single _nonSelectAlpha; // 0x28
	private Single _haveSelectAlpha; // 0x2c
	private UIStateFinder m_stateFinder; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderFragList; // 0x8
	private static DelegateBridge __Hotfix0_ClearAllFrag; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2334ea0 VA: 0x759494cea0
	public Void Render(TuningProductViewModel model) { }
	// RVA: 0x2334ff4 VA: 0x759494cff4
	private Void _RenderFragList(ListDict`2 fragListDict) { }
	// RVA: 0x23351dc VA: 0x759494d1dc
	public Void ClearAllFrag() { }
	// RVA: 0x2335280 VA: 0x759494d280
	public Void .ctor() { }
}
```