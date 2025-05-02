# UIBattleSandboxConstructItemPair

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Boolean _alwwaysShowNormalColor`

- `Boolean _doNotUseIconColor`

- `Image _iconImage`

- `Text _valueTxt`

- `Color _normalColor`

- `Color _notEnoughColor`

- `Color _addColor`

- `Single _tweenTime`

- `Ease _tweenEase`

- `Boolean _enableImg`

- `Int32 _maxVal`

- `String _maxValText`

- `Int32 m_oldVal`

- `Int32 m_targetVal`

- `Tween m_tween`


## Methods

- `Void Render(SandboxConstructItemPairModel)`

- `Color _GetColor(SandboxConstructItemPairModel)`

- `Sprite _GetIcon(String, String)`

- `Color _GetIconColor(String, String, Single)`

- `String _GetText(SandboxConstructItemPairModel)`

- `Void _RenterTextTween(SandboxConstructItemPairModel)`

- `Void <_RenterTextTween>b__21_1(Single)`

- `Void <_RenterTextTween>b__21_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxConstructItemPair : ConstructCommonUIBase
{
	private Boolean _alwwaysShowNormalColor; // 0x18
	private Boolean _doNotUseIconColor; // 0x19
	private Image _iconImage; // 0x20
	private Text _valueTxt; // 0x28
	private Color _normalColor; // 0x30
	private Color _notEnoughColor; // 0x40
	private Color _addColor; // 0x50
	private Single _tweenTime; // 0x60
	private Ease _tweenEase; // 0x64
	private Boolean _enableImg; // 0x68
	private Int32 _maxVal; // 0x6c
	private String _maxValText; // 0x70
	private Int32 m_oldVal; // 0x78
	private Int32 m_targetVal; // 0x7c
	private Tween m_tween; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GetColor; // 0x8
	private static DelegateBridge __Hotfix0__GetIcon; // 0x10
	private static DelegateBridge __Hotfix0__GetIconColor; // 0x18
	private static DelegateBridge __Hotfix0__GetText; // 0x20
	private static DelegateBridge __Hotfix0__RenterTextTween; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x20bf31c VA: 0x75946d731c
	public Void Render(SandboxConstructItemPairModel model) { }
	// RVA: 0x20bfc54 VA: 0x75946d7c54
	private Color _GetColor(SandboxConstructItemPairModel model) { }
	// RVA: 0x20bf49c VA: 0x75946d749c
	private Sprite _GetIcon(String topicId, String itemId) { }
	// RVA: 0x20bf624 VA: 0x75946d7624
	private Color _GetIconColor(String topicId, String itemId, Single alpha) { }
	// RVA: 0x20bfb54 VA: 0x75946d7b54
	private String _GetText(SandboxConstructItemPairModel model) { }
	// RVA: 0x20bf7b0 VA: 0x75946d77b0
	private Void _RenterTextTween(SandboxConstructItemPairModel model) { }
	// RVA: 0x20bfd7c VA: 0x75946d7d7c
	public Void .ctor() { }
	// RVA: 0x20bfe3c VA: 0x75946d7e3c
	private Void <_RenterTextTween>b__21_1(Single val) { }
	// RVA: 0x20bff20 VA: 0x75946d7f20
	private Void <_RenterTextTween>b__21_2() { }
}
```