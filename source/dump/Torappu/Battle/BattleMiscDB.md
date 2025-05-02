# BattleMiscDB

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean TryGetSceneId(String, out)`

- `Void EditorGrabMapPreviewPath()`

- `Void EditorCollectBlackList(Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleMiscDB : ConstTable`2
{
	private static DelegateBridge __Hotfix0_TryGetSceneId; // 0x0
	private static DelegateBridge __Hotfix0_GetEffectBlackListOrNull; // 0x8
	private static DelegateBridge __Hotfix0_EditorGrabMapPreviewPath; // 0x10
	private static DelegateBridge __Hotfix0_EditorCollectBlackList; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c5509c VA: 0x759426d09c
	public Boolean TryGetSceneId(String levelId, out LevelScenePair levelScenePair) { }
	// RVA: 0x1c5519c VA: 0x759426d19c
	public List`1 GetEffectBlackListOrNull(String skillId) { }
	// RVA: 0x1c552e8 VA: 0x759426d2e8
	public Void EditorGrabMapPreviewPath() { }
	// RVA: 0x1c5534c VA: 0x759426d34c
	public Void EditorCollectBlackList(Dictionary`2 blacklist) { }
	// RVA: 0x1c553c4 VA: 0x759426d3c4
	public Void .ctor() { }
}
```