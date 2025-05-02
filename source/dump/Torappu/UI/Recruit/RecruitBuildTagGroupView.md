# RecruitBuildTagGroupView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RecruitBuildTagView _normalTagPrefab`

- `RecruitBuildTagView _specialTagPrefab`

- `Transform _container`


## Methods

- `Void Render(BuildTagModel[])`

- `RecruitBuildTagView _AllocNormalTag()`

- `RecruitBuildTagView _AllocSpecialTag()`

- `Void _RemoveNormalTag(RecruitBuildTagView)`

- `Void _RemoveSpecialTag(RecruitBuildTagView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildTagGroupView : MonoBehaviour
{
	private RecruitBuildTagView _normalTagPrefab; // 0x18
	private RecruitBuildTagView _specialTagPrefab; // 0x20
	private Transform _container; // 0x28
	private List`1 m_normalTagInsts; // 0x30
	private List`1 m_specialTagInsts; // 0x38


	// RVA: 0x2706de4 VA: 0x7594d1ede4
	public Void Render(BuildTagModel[] tags) { }
	// RVA: 0x2706fd4 VA: 0x7594d1efd4
	private Queue`1 _BuildPool(List`1 list) { }
	// RVA: 0x27071d4 VA: 0x7594d1f1d4
	private RecruitBuildTagView _AllocNormalTag() { }
	// RVA: 0x27070cc VA: 0x7594d1f0cc
	private RecruitBuildTagView _AllocSpecialTag() { }
	// RVA: 0x27073d0 VA: 0x7594d1f3d0
	private Void _RemoveNormalTag(RecruitBuildTagView inst) { }
	// RVA: 0x2707360 VA: 0x7594d1f360
	private Void _RemoveSpecialTag(RecruitBuildTagView inst) { }
	// RVA: 0x2707440 VA: 0x7594d1f440
	public Void .ctor() { }
}
```