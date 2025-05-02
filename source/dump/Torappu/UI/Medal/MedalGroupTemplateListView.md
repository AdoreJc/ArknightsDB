# MedalGroupTemplateListView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalGroupListLoopAdapter _recycleList`

- `LoopVerticalScrollRect _scrollRect`

- `Tween m_cacheTween`


## Methods

- `Void ToGroup(String)`

- `Void _ToGroupPos(Int32)`

- `Void Render(MedalListViewModel)`

- `Single <_ToGroupPos>b__4_0()`

- `Void <_ToGroupPos>b__4_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupTemplateListView : MonoBehaviour, IHotfixable
{
	private MedalGroupListLoopAdapter _recycleList; // 0x18
	private LoopVerticalScrollRect _scrollRect; // 0x20
	private Tween m_cacheTween; // 0x28
	private List`1 m_cacheGroupList; // 0x30
	private static DelegateBridge __Hotfix0_ToGroup; // 0x0
	private static DelegateBridge __Hotfix0__ToGroupPos; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x279e0c4 VA: 0x7594db60c4
	public Void ToGroup(String groupId) { }
	// RVA: 0x279e1c4 VA: 0x7594db61c4
	private Void _ToGroupPos(Int32 index) { }
	// RVA: 0x2796f4c VA: 0x7594daef4c
	public Void Render(MedalListViewModel listViewModel) { }
	// RVA: 0x279e3b0 VA: 0x7594db63b0
	public Void .ctor() { }
	// RVA: 0x279e420 VA: 0x7594db6420
	private Single <_ToGroupPos>b__4_0() { }
	// RVA: 0x279e43c VA: 0x7594db643c
	private Void <_ToGroupPos>b__4_1(Single val) { }
}
```