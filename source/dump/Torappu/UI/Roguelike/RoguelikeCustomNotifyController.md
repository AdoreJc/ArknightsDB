# RoguelikeCustomNotifyController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _notifyContainer`


## Methods

- `Void DoNotify(String, ValueBundle, ILoadAsset)`

- `Void _TriggerNotifyComplete(RoguelikeCustomNotifyType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCustomNotifyController : MonoBehaviour, IHotfixable
{
	private RectTransform _notifyContainer; // 0x18
	private Dictionary`2 m_customNotifyDict; // 0x20
	private static DelegateBridge __Hotfix0_DoNotify; // 0x0
	private static DelegateBridge __Hotfix0__TriggerNotifyComplete; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29f80b4 VA: 0x75950100b4
	public Void DoNotify(String path, ValueBundle options, ILoadAsset iLoadAsset) { }
	// RVA: 0x29f8354 VA: 0x7595010354
	private Void _TriggerNotifyComplete(RoguelikeCustomNotifyType notifyType) { }
	// RVA: 0x29f848c VA: 0x759501048c
	public Void .ctor() { }
}
```