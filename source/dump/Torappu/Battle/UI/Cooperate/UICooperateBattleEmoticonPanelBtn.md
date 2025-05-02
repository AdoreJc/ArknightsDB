# UICooperateBattleEmoticonPanelBtn

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `UIAnimationLocation _activeAnim`

- `Button _button`

- `CanvasGroup _itemCanvasGroup`

- `Single _showDuration`

- `Single _inactiveAlpha`

- `Single _activeAlpha`

- `CooperateUIPlugin m_plugin`

- `Tween m_tween`

- `Tween m_tweenActive`

- `Boolean m_isActive`


## Methods

- `Void OnButtonClicked()`

- `Void Show(Single)`

- `Void RecoverFromCD()`

- `Void SetInCD()`

- `Void <RecoverFromCD>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateBattleEmoticonPanelBtn : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _activeAnim; // 0x18
	private Button _button; // 0x28
	private CanvasGroup _itemCanvasGroup; // 0x30
	private Single _showDuration; // 0x38
	private Single _inactiveAlpha; // 0x3c
	private Single _activeAlpha; // 0x40
	private CooperateUIPlugin m_plugin; // 0x48
	private Tween m_tween; // 0x50
	private Tween m_tweenActive; // 0x58
	private Boolean m_isActive; // 0x60
	private static DelegateBridge __Hotfix0_OnButtonClicked; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_RecoverFromCD; // 0x10
	private static DelegateBridge __Hotfix0_SetInCD; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20e2280 VA: 0x75946fa280
	public Void OnButtonClicked() { }
	// RVA: 0x20e1bb8 VA: 0x75946f9bb8
	public Void Show(Single predelay) { }
	// RVA: 0x20e0ef8 VA: 0x75946f8ef8
	public Void RecoverFromCD() { }
	// RVA: 0x20e0d40 VA: 0x75946f8d40
	public Void SetInCD() { }
	// RVA: 0x20e245c VA: 0x75946fa45c
	public Void .ctor() { }
	// RVA: 0x20e24e8 VA: 0x75946fa4e8
	private Void <RecoverFromCD>b__12_0() { }
}
```