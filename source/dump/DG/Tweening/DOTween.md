# DOTween

**Namespace:** `DG.Tweening`


## Dump
```C#
// Dll : DOTween.dll
// Namespace : DG.Tweening
public class DOTween
{
	public static readonly String Version; // 0x0
	public static Boolean useSafeMode; // 0x8
	public static SafeModeLogBehaviour safeModeLogBehaviour; // 0xc
	public static NestedTweenFailureBehaviour nestedTweenFailureBehaviour; // 0x10
	public static Boolean showUnityEditorReport; // 0x14
	public static Single timeScale; // 0x18
	public static Single unscaledTimeScale; // 0x1c
	public static Boolean useSmoothDeltaTime; // 0x20
	public static Single maxSmoothUnscaledTime; // 0x24
	internal static RewindCallbackMode rewindCallbackMode; // 0x28
	private static LogBehaviour _logBehaviour; // 0x2c
	public static Func`3 onWillLog; // 0x30
	public static Boolean drawGizmos; // 0x38
	public static Boolean debugMode; // 0x39
	private static Boolean _fooDebugStoreTargetId; // 0x3a
	public static UpdateType defaultUpdateType; // 0x3c
	public static Boolean defaultTimeScaleIndependent; // 0x40
	public static AutoPlay defaultAutoPlay; // 0x44
	public static Boolean defaultAutoKill; // 0x48
	public static LoopType defaultLoopType; // 0x4c
	public static Boolean defaultRecyclable; // 0x50
	public static Ease defaultEaseType; // 0x54
	public static Single defaultEaseOvershootOrAmplitude; // 0x58
	public static Single defaultEasePeriod; // 0x5c
	public static DOTweenComponent instance; // 0x60
	private static Boolean _foo_isQuitting; // 0x68
	internal static Int32 maxActiveTweenersReached; // 0x6c
	internal static Int32 maxActiveSequencesReached; // 0x70
	internal static SafeModeReport safeModeReport; // 0x74
	internal static readonly List`1 GizmosDelegates; // 0x88
	internal static Boolean initialized; // 0x90
	private static Int32 _isQuittingFrame; // 0x94

	public static LogBehaviour logBehaviour { get; set; }
	public static Boolean debugStoreTargetId { get; set; }
	internal static Boolean isQuitting { get; set; }

	// RVA: 0x4164708 VA: 0x759677c708
	public static LogBehaviour get_logBehaviour() { }
	// RVA: 0x4164760 VA: 0x759677c760
	public static Void set_logBehaviour(LogBehaviour value) { }
	// RVA: 0x41647c4 VA: 0x759677c7c4
	public static Boolean get_debugStoreTargetId() { }
	// RVA: 0x4164864 VA: 0x759677c864
	public static Void set_debugStoreTargetId(Boolean value) { }
	// RVA: 0x41648c0 VA: 0x759677c8c0
	internal static Boolean get_isQuitting() { }
	// RVA: 0x4164988 VA: 0x759677c988
	internal static Void set_isQuitting(Boolean value) { }
	// RVA: 0x4164a20 VA: 0x759677ca20
	public static IDOTweenInit Init(Nullable`1 recycleAllByDefault, Nullable`1 useSafeMode, Nullable`1 logBehaviour) { }
	// RVA: 0x41652a8 VA: 0x759677d2a8
	private static Void AutoInit() { }
	// RVA: 0x4164b7c VA: 0x759677cb7c
	private static IDOTweenInit Init(DOTweenSettings settings, Nullable`1 recycleAllByDefault, Nullable`1 useSafeMode, Nullable`1 logBehaviour) { }
	// RVA: 0x41653a0 VA: 0x759677d3a0
	public static Void SetTweensCapacity(Int32 tweenersCapacity, Int32 sequencesCapacity) { }
	// RVA: 0x4165408 VA: 0x759677d408
	public static Void Clear(Boolean destroy) { }
	// RVA: 0x4165460 VA: 0x759677d460
	internal static Void Clear(Boolean destroy, Boolean isApplicationQuitting) { }
	// RVA: 0x41655e0 VA: 0x759677d5e0
	public static Void ClearCachedTweens() { }
	// RVA: 0x4165630 VA: 0x759677d630
	public static Int32 Validate() { }
	// RVA: 0x4165680 VA: 0x759677d680
	public static Void ManualUpdate(Single deltaTime, Single unscaledDeltaTime) { }
	// RVA: 0x4165810 VA: 0x759677d810
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Single endValue, Single duration) { }
	// RVA: 0x41658a8 VA: 0x759677d8a8
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Double endValue, Single duration) { }
	// RVA: 0x4165940 VA: 0x759677d940
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Int32 endValue, Single duration) { }
	// RVA: 0x41659d8 VA: 0x759677d9d8
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, UInt32 endValue, Single duration) { }
	// RVA: 0x4165a70 VA: 0x759677da70
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Int64 endValue, Single duration) { }
	// RVA: 0x4165b08 VA: 0x759677db08
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, UInt64 endValue, Single duration) { }
	// RVA: 0x4165ba0 VA: 0x759677dba0
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, String endValue, Single duration) { }
	// RVA: 0x4165c38 VA: 0x759677dc38
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Vector2 endValue, Single duration) { }
	// RVA: 0x4165ce0 VA: 0x759677dce0
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Vector3 endValue, Single duration) { }
	// RVA: 0x4165d90 VA: 0x759677dd90
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Vector4 endValue, Single duration) { }
	// RVA: 0x4165e50 VA: 0x759677de50
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Vector3 endValue, Single duration) { }
	// RVA: 0x4165f00 VA: 0x759677df00
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Color endValue, Single duration) { }
	// RVA: 0x4165fc0 VA: 0x759677dfc0
	public static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Rect endValue, Single duration) { }
	// RVA: 0x4166080 VA: 0x759677e080
	public static Tweener To(DOGetter`1 getter, DOSetter`1 setter, RectOffset endValue, Single duration) { }
	// RVA: 0x VA: 0x0
	public static TweenerCore`3 To(ABSTweenPlugin`3 plugin, DOGetter`1 getter, DOSetter`1 setter, T2 endValue, Single duration) { }
	// RVA: 0x4166118 VA: 0x759677e118
	public static TweenerCore`3 ToAxis(DOGetter`1 getter, DOSetter`1 setter, Single endValue, Single duration, AxisConstraint axisConstraint) { }
	// RVA: 0x41661cc VA: 0x759677e1cc
	public static TweenerCore`3 ToAlpha(DOGetter`1 getter, DOSetter`1 setter, Single endValue, Single duration) { }
	// RVA: 0x41662a0 VA: 0x759677e2a0
	public static Tweener To(DOSetter`1 setter, Single startValue, Single endValue, Single duration) { }
	// RVA: 0x4166420 VA: 0x759677e420
	public static TweenerCore`3 Punch(DOGetter`1 getter, DOSetter`1 setter, Vector3 direction, Single duration, Int32 vibrato, Single elasticity) { }
	// RVA: 0x4166a48 VA: 0x759677ea48
	public static TweenerCore`3 Shake(DOGetter`1 getter, DOSetter`1 setter, Single duration, Single strength, Int32 vibrato, Single randomness, Boolean ignoreZAxis, Boolean fadeOut, ShakeRandomnessMode randomnessMode) { }
	// RVA: 0x4167340 VA: 0x759677f340
	public static TweenerCore`3 Shake(DOGetter`1 getter, DOSetter`1 setter, Single duration, Vector3 strength, Int32 vibrato, Single randomness, Boolean fadeOut, ShakeRandomnessMode randomnessMode) { }
	// RVA: 0x4166b10 VA: 0x759677eb10
	private static TweenerCore`3 Shake(DOGetter`1 getter, DOSetter`1 setter, Single duration, Vector3 strength, Int32 vibrato, Single randomness, Boolean ignoreZAxis, Boolean vectorBased, Boolean fadeOut, ShakeRandomnessMode randomnessMode) { }
	// RVA: 0x4166810 VA: 0x759677e810
	public static TweenerCore`3 ToArray(DOGetter`1 getter, DOSetter`1 setter, Vector3[] endValues, Single[] durations) { }
	// RVA: 0x416740c VA: 0x759677f40c
	internal static TweenerCore`3 To(DOGetter`1 getter, DOSetter`1 setter, Color2 endValue, Single duration) { }
	// RVA: 0x41674c0 VA: 0x759677f4c0
	public static Sequence Sequence() { }
	// RVA: 0x416761c VA: 0x759677f61c
	public static Sequence Sequence(Object target) { }
	// RVA: 0x416768c VA: 0x759677f68c
	public static Int32 CompleteAll(Boolean withCallbacks) { }
	// RVA: 0x4167700 VA: 0x759677f700
	public static Int32 Complete(Object targetOrId, Boolean withCallbacks) { }
	// RVA: 0x416778c VA: 0x759677f78c
	internal static Int32 CompleteAndReturnKilledTot() { }
	// RVA: 0x41677f8 VA: 0x759677f7f8
	internal static Int32 CompleteAndReturnKilledTot(Object targetOrId) { }
	// RVA: 0x416787c VA: 0x759677f87c
	internal static Int32 CompleteAndReturnKilledTot(Object target, Object id) { }
	// RVA: 0x4167908 VA: 0x759677f908
	internal static Int32 CompleteAndReturnKilledTotExceptFor(Object[] excludeTargetsOrIds) { }
	// RVA: 0x4167978 VA: 0x759677f978
	public static Int32 FlipAll() { }
	// RVA: 0x41679e4 VA: 0x759677f9e4
	public static Int32 Flip(Object targetOrId) { }
	// RVA: 0x4167a68 VA: 0x759677fa68
	public static Int32 GotoAll(Single to, Boolean andPlay) { }
	// RVA: 0x4167ae4 VA: 0x759677fae4
	public static Int32 Goto(Object targetOrId, Single to, Boolean andPlay) { }
	// RVA: 0x4167b7c VA: 0x759677fb7c
	public static Int32 KillAll(Boolean complete) { }
	// RVA: 0x4167c10 VA: 0x759677fc10
	public static Int32 KillAll(Boolean complete, Object[] idsOrTargetsToExclude) { }
	// RVA: 0x4167d10 VA: 0x759677fd10
	public static Int32 Kill(Object targetOrId, Boolean complete) { }
	// RVA: 0x4167dd4 VA: 0x759677fdd4
	public static Int32 Kill(Object target, Object id, Boolean complete) { }
	// RVA: 0x4167ea8 VA: 0x759677fea8
	public static Int32 PauseAll() { }
	// RVA: 0x4167f14 VA: 0x759677ff14
	public static Int32 Pause(Object targetOrId) { }
	// RVA: 0x4167f98 VA: 0x759677ff98
	public static Int32 PlayAll() { }
	// RVA: 0x4168004 VA: 0x7596780004
	public static Int32 Play(Object targetOrId) { }
	// RVA: 0x4168088 VA: 0x7596780088
	public static Int32 Play(Object target, Object id) { }
	// RVA: 0x4168114 VA: 0x7596780114
	public static Int32 PlayBackwardsAll() { }
	// RVA: 0x4168180 VA: 0x7596780180
	public static Int32 PlayBackwards(Object targetOrId) { }
	// RVA: 0x4168204 VA: 0x7596780204
	public static Int32 PlayBackwards(Object target, Object id) { }
	// RVA: 0x4168290 VA: 0x7596780290
	public static Int32 PlayForwardAll() { }
	// RVA: 0x41682fc VA: 0x75967802fc
	public static Int32 PlayForward(Object targetOrId) { }
	// RVA: 0x4168380 VA: 0x7596780380
	public static Int32 PlayForward(Object target, Object id) { }
	// RVA: 0x416840c VA: 0x759678040c
	public static Int32 RestartAll(Boolean includeDelay) { }
	// RVA: 0x416847c VA: 0x759678047c
	public static Int32 Restart(Object targetOrId, Boolean includeDelay, Single changeDelayTo) { }
	// RVA: 0x4168514 VA: 0x7596780514
	public static Int32 Restart(Object target, Object id, Boolean includeDelay, Single changeDelayTo) { }
	// RVA: 0x41685c0 VA: 0x75967805c0
	public static Int32 RewindAll(Boolean includeDelay) { }
	// RVA: 0x4168630 VA: 0x7596780630
	public static Int32 Rewind(Object targetOrId, Boolean includeDelay) { }
	// RVA: 0x41686b8 VA: 0x75967806b8
	public static Int32 SmoothRewindAll() { }
	// RVA: 0x4168724 VA: 0x7596780724
	public static Int32 SmoothRewind(Object targetOrId) { }
	// RVA: 0x41687a8 VA: 0x75967807a8
	public static Int32 TogglePauseAll() { }
	// RVA: 0x4168814 VA: 0x7596780814
	public static Int32 TogglePause(Object targetOrId) { }
	// RVA: 0x4168898 VA: 0x7596780898
	public static Boolean IsTweening(Object targetOrId, Boolean alsoCheckIfIsPlaying) { }
	// RVA: 0x4168920 VA: 0x7596780920
	public static Int32 TotalActiveTweens() { }
	// RVA: 0x4168978 VA: 0x7596780978
	public static Int32 TotalActiveTweeners() { }
	// RVA: 0x41689d0 VA: 0x75967809d0
	public static Int32 TotalActiveSequences() { }
	// RVA: 0x4168a28 VA: 0x7596780a28
	public static Int32 TotalPlayingTweens() { }
	// RVA: 0x4168a78 VA: 0x7596780a78
	public static Int32 TotalTweensById(Object id, Boolean playingOnly) { }
	// RVA: 0x4168aec VA: 0x7596780aec
	public static List`1 PlayingTweens(List`1 fillableList) { }
	// RVA: 0x4168b7c VA: 0x7596780b7c
	public static List`1 PausedTweens(List`1 fillableList) { }
	// RVA: 0x4168c0c VA: 0x7596780c0c
	public static List`1 TweensById(Object id, Boolean playingOnly, List`1 fillableList) { }
	// RVA: 0x4168cc8 VA: 0x7596780cc8
	public static List`1 TweensByTarget(Object target, Boolean playingOnly, List`1 fillableList) { }
	// RVA: 0x4165774 VA: 0x759677d774
	private static Void InitCheck() { }
	// RVA: 0x VA: 0x0
	private static TweenerCore`3 ApplyTo(DOGetter`1 getter, DOSetter`1 setter, T2 endValue, Single duration, ABSTweenPlugin`3 plugin) { }
	// RVA: 0x4168d6c VA: 0x7596780d6c
	public Void .ctor() { }
	// RVA: 0x4168d74 VA: 0x7596780d74
	private static Void .cctor() { }
}
```