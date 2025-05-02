# ContinuousBattleSelectTimesItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _objSelected`

- `GameObject _objNeedApItem`

- `Color _colorNeedBuyAp`

- `Color _colorNotNeedBuyAp`

- `Text _textTimes`

- `GameObject _objSplit`

- `Int32 m_times`


## Methods

- `Void Render(RenderOptions)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ContinuousBattleSelectTimesItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objSelected; // 0x18
	private GameObject _objNeedApItem; // 0x20
	private Color _colorNeedBuyAp; // 0x28
	private Color _colorNotNeedBuyAp; // 0x38
	private Text _textTimes; // 0x48
	private GameObject _objSplit; // 0x50
	private Action`1 m_actionClick; // 0x58
	private Int32 m_times; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f8cfb4 VA: 0x75955a4fb4
	public Void Render(RenderOptions renderOptions) { }
	// RVA: 0x2f8d15c VA: 0x75955a515c
	public Void OnClick() { }
	// RVA: 0x2f8d1e4 VA: 0x75955a51e4
	public Void .ctor() { }
}
```