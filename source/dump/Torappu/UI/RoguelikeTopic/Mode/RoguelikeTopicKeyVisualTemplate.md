# RoguelikeTopicKeyVisualTemplate

**Namespace:** `Torappu.UI.RoguelikeTopic.Mode`


## Fields

- `GameObject _bg`

- `GameObject _effect`

- `GameObject _fg`


## Methods

- `Void AttachBackground(Transform)`

- `GameObject AttachEffect(Transform)`

- `Void AttachForeground(Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Mode
public class RoguelikeTopicKeyVisualTemplate : MonoBehaviour, IHotfixable
{
	private GameObject _bg; // 0x18
	private GameObject _effect; // 0x20
	private GameObject _fg; // 0x28
	private static DelegateBridge __Hotfix0_AttachBackground; // 0x0
	private static DelegateBridge __Hotfix0_AttachEffect; // 0x8
	private static DelegateBridge __Hotfix0_AttachForeground; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26d59b8 VA: 0x7594ced9b8
	public Void AttachBackground(Transform root) { }
	// RVA: 0x26d5a7c VA: 0x7594ceda7c
	public GameObject AttachEffect(Transform root) { }
	// RVA: 0x26d5b40 VA: 0x7594cedb40
	public Void AttachForeground(Transform root) { }
	// RVA: 0x26d5c38 VA: 0x7594cedc38
	public Void .ctor() { }
}
```