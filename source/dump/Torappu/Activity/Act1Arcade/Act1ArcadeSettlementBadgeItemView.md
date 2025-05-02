# Act1ArcadeSettlementBadgeItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Image _imgBadge`

- `UIAnimationLocation _startAnim`

- `AutoPackSpriteHub m_catchedHub`

- `Tween m_animTween`


## Methods

- `Void OnRender(String, UnlockBadgeModel, Single)`

- `Sprite _LoadBadgeBookBadgeIcon(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementBadgeItemView : MonoBehaviour, IHotfixable
{
	private Image _imgBadge; // 0x18
	private UIAnimationLocation _startAnim; // 0x20
	private AutoPackSpriteHub m_catchedHub; // 0x30
	private Tween m_animTween; // 0x38
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__LoadBadgeBookBadgeIcon; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3405d08 VA: 0x7595a1dd08
	public Void OnRender(String actId, UnlockBadgeModel badgeModel, Single animStartDelay) { }
	// RVA: 0x3405ebc VA: 0x7595a1debc
	private Sprite _LoadBadgeBookBadgeIcon(String actId, String iconId) { }
	// RVA: 0x3406058 VA: 0x7595a1e058
	public Void .ctor() { }
}
```