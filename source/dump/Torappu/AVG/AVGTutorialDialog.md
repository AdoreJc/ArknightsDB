# AVGTutorialDialog

**Namespace:** `Torappu.AVG`


## Fields

- `AVGTypeWriterText _typeWriter`

- `Image _headImage`

- `Single _defaultFadeTime`

- `Vector2 _defaultPos`

- `CanvasGroup m_group`


## Properties

- `Boolean IsTyping`


## Methods

- `Boolean get_IsTyping()`

- `Void OnReset()`

- `Void Show(Command, Sprite)`

- `Void ForceEnd()`

- `Void Hide()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGTutorialDialog : MonoBehaviour, IHotfixable
{
	private AVGTypeWriterText _typeWriter; // 0x18
	private Image _headImage; // 0x20
	private Single _defaultFadeTime; // 0x28
	private Vector2 _defaultPos; // 0x2c
	private CanvasGroup m_group; // 0x38
	private static DelegateBridge __Hotfix0_get_IsTyping; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0_ForceEnd; // 0x18
	private static DelegateBridge __Hotfix0_Hide; // 0x20
	private static DelegateBridge __Hotfix0_Awake; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean IsTyping { get; }

	// RVA: 0x3eaccc8 VA: 0x75964c4cc8
	public Boolean get_IsTyping() { }
	// RVA: 0x3eacd38 VA: 0x75964c4d38
	public Void OnReset() { }
	// RVA: 0x3eacdf0 VA: 0x75964c4df0
	public Void Show(Command command, Sprite head) { }
	// RVA: 0x3ead094 VA: 0x75964c5094
	public Void ForceEnd() { }
	// RVA: 0x3ead104 VA: 0x75964c5104
	public Void Hide() { }
	// RVA: 0x3ead1f4 VA: 0x75964c51f4
	private Void Awake() { }
	// RVA: 0x3ead284 VA: 0x75964c5284
	public Void .ctor() { }
}
```