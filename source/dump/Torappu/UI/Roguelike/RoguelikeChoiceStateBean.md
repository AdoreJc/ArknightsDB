# RoguelikeChoiceStateBean

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeChoiceScene m_scene`


## Properties

- `RoguelikeChoiceScene scene`


## Methods

- `RoguelikeChoiceScene get_scene()`

- `Boolean TryUpdateData(String)`

- `SceneContent _GetPlayerChoiceScene(PlayerStatus)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceStateBean : IStateBean, IHotfixable
{
	private RoguelikeChoiceScene m_scene; // 0x10
	private static DelegateBridge __Hotfix0_get_scene; // 0x0
	private static DelegateBridge __Hotfix0_TryUpdateData; // 0x8
	private static DelegateBridge __Hotfix0__GetPlayerChoiceScene; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public RoguelikeChoiceScene scene { get; }

	// RVA: 0x29f0068 VA: 0x7595008068
	public RoguelikeChoiceScene get_scene() { }
	// RVA: 0x29f0828 VA: 0x7595008828
	public Boolean TryUpdateData(String topicId) { }
	// RVA: 0x29f112c VA: 0x759500912c
	private SceneContent _GetPlayerChoiceScene(PlayerStatus playerStatus) { }
	// RVA: 0x29f0bb8 VA: 0x7595008bb8
	public Void .ctor() { }
}
```