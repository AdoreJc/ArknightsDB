# Act13sideFinishMissionView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Image _orgIcon`

- `Image _orgInfo`

- `Text _finishState`

- `GameObject _fromToPart`

- `Text _initPer`

- `Text _endPer`

- `GameObject _atMaxPart`

- `GameObject _gradeUpPart`

- `Text _initGrade`

- `Text _endGrade`

- `GameObject _skipPart`

- `Text _nextDetail`

- `CanvasGroup _alphaCanvasGroup`

- `AnimationWrapper _animWrapper`

- `Boolean isFirstTime`


## Methods

- `Void _RenderView(String, String, Int32, Int32, Act13SideEachMissionInfo, LongTermMissionData)`

- `Void RenderInfo(String, String, Int32, Int32, Act13SideEachMissionInfo, LongTermMissionData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideFinishMissionView : MonoBehaviour, IHotfixable
{
	private Image _orgIcon; // 0x18
	private Image _orgInfo; // 0x20
	private Text _finishState; // 0x28
	private GameObject _fromToPart; // 0x30
	private Text _initPer; // 0x38
	private Text _endPer; // 0x40
	private GameObject _atMaxPart; // 0x48
	private GameObject _gradeUpPart; // 0x50
	private Text _initGrade; // 0x58
	private Text _endGrade; // 0x60
	private GameObject _skipPart; // 0x68
	private Text _nextDetail; // 0x70
	private CanvasGroup _alphaCanvasGroup; // 0x78
	private AnimationWrapper _animWrapper; // 0x80
	public Boolean isFirstTime; // 0x88
	private const String ANIM_PARAM; // 0x0
	private static DelegateBridge __Hotfix0__RenderView; // 0x0
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3441020 VA: 0x7595a59020
	private Void _RenderView(String actId, String orgId, Int32 index, Int32 total, Act13SideEachMissionInfo eachMissionInfo, LongTermMissionData data) { }
	// RVA: 0x3441540 VA: 0x7595a59540
	public Void RenderInfo(String actId, String orgId, Int32 index, Int32 total, Act13SideEachMissionInfo eachMissionInfo, LongTermMissionData data) { }
	// RVA: 0x3441624 VA: 0x7595a59624
	public Void .ctor() { }
}
```