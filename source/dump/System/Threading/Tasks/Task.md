# Task

**Namespace:** `System.Threading.Tasks`


## Fields

- `Int32 m_taskId`

- `Object m_continuationObject`


## Properties

- `Int32 Id`

- `AggregateException Exception`

- `TaskStatus Status`

- `Boolean IsCanceled`

- `Boolean IsCompleted`

- `Boolean IsCompletedSuccessfully`

- `TaskCreationOptions CreationOptions`

- `Object AsyncState`

- `Boolean IsFaulted`


## Methods

- `Void AssignCancellationToken(CancellationToken, Task, TaskContinuation)`

- `Void NotifyDebuggerOfWaitCompletion()`

- `Int32 get_Id()`

- `AggregateException get_Exception()`

- `TaskStatus get_Status()`

- `Boolean get_IsCanceled()`

- `ContingentProperties EnsureContingentPropertiesInitializedCore(Boolean)`

- `Boolean get_IsCompleted()`

- `Boolean get_IsCompletedSuccessfully()`

- `TaskCreationOptions get_CreationOptions()`

- `Object get_AsyncState()`

- `Boolean get_IsFaulted()`

- `Void Dispose()`

- `AggregateException GetExceptions(Boolean)`

- `Void Execute()`

- `Void HandleException(Exception)`

- `TaskAwaiter GetAwaiter()`

- `ConfiguredTaskAwaitable ConfigureAwait(Boolean)`

- `Void Wait()`

- `Boolean Wait(Int32, CancellationToken)`

- `Boolean WrappedTryRunInline()`

- `Boolean SpinThenBlockingWait(Int32, CancellationToken)`

- `Boolean SpinWait(Int32)`

- `Void SetCancellationAcknowledged()`

- `Void LogFinishCompletionNotification()`

- `Task ContinueWith(Action`1)`

- `Task ContinueWith(Action`1, TaskScheduler, CancellationToken, TaskContinuationOptions)`

- `Task ContinueWith(Action`2, Object, CancellationToken, TaskContinuationOptions, TaskScheduler)`

- `Task ContinueWith(Action`2, Object, TaskScheduler, CancellationToken, TaskContinuationOptions)`

- `Void AddCompletionAction(ITaskCompletionAction, Boolean)`

- `Boolean AddTaskContinuationComplex(Object, Boolean)`

- `Boolean AddTaskContinuation(Object, Boolean)`

- `Void MarkAborted(ThreadAbortException)`

- `Void ExecuteWithThreadLocal(ref)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Threading.Tasks
public class Task : IThreadPoolWorkItem, IAsyncResult, IDisposable
{
	internal static Int32 s_taskIdCounter; // 0x0
	private Int32 m_taskId; // 0x10
	internal Delegate m_action; // 0x18
	internal Object m_stateObject; // 0x20
	internal TaskScheduler m_taskScheduler; // 0x28
	internal readonly Task m_parent; // 0x30
	internal Int32 m_stateFlags; // 0x38
	private const Int32 OptionsMask; // 0x0
	internal const Int32 TASK_STATE_STARTED; // 0x0
	internal const Int32 TASK_STATE_DELEGATE_INVOKED; // 0x0
	internal const Int32 TASK_STATE_DISPOSED; // 0x0
	internal const Int32 TASK_STATE_EXCEPTIONOBSERVEDBYPARENT; // 0x0
	internal const Int32 TASK_STATE_CANCELLATIONACKNOWLEDGED; // 0x0
	internal const Int32 TASK_STATE_FAULTED; // 0x0
	internal const Int32 TASK_STATE_CANCELED; // 0x0
	internal const Int32 TASK_STATE_WAITING_ON_CHILDREN; // 0x0
	internal const Int32 TASK_STATE_RAN_TO_COMPLETION; // 0x0
	internal const Int32 TASK_STATE_WAITINGFORACTIVATION; // 0x0
	internal const Int32 TASK_STATE_COMPLETION_RESERVED; // 0x0
	internal const Int32 TASK_STATE_THREAD_WAS_ABORTED; // 0x0
	internal const Int32 TASK_STATE_WAIT_COMPLETION_NOTIFICATION; // 0x0
	private const Int32 TASK_STATE_COMPLETED_MASK; // 0x0
	private const Int32 CANCELLATION_REQUESTED; // 0x0
	private Object m_continuationObject; // 0x40
	private static readonly Object s_taskCompletionSentinel; // 0x8
	internal static Boolean s_asyncDebuggingEnabled; // 0x10
	internal ContingentProperties m_contingentProperties; // 0x48
	private static readonly Action`1 s_taskCancelCallback; // 0x18
	internal static Task t_currentTask; // 0xffffffffffffffff
	private static StackGuard t_stackGuard; // 0xffffffffffffffff
	private static readonly Func`1 s_createContingentProperties; // 0x20
	private static readonly TaskFactory <Factory>k__BackingField; // 0x28
	private static readonly Task <CompletedTask>k__BackingField; // 0x30
	private static readonly Predicate`1 s_IsExceptionObservedByParentPredicate; // 0x38
	private static ContextCallback s_ecCallback; // 0x40
	private static readonly Predicate`1 s_IsTaskContinuationNullPredicate; // 0x48
	private static readonly Dictionary`2 s_currentActiveTasks; // 0x50
	private static readonly Object s_activeTasksLock; // 0x58

	internal TaskCreationOptions Options { get; }
	internal Boolean IsWaitNotificationEnabledOrNotRanToCompletion { get; }
	internal virtual Boolean ShouldNotifyDebuggerOfWaitCompletion { get; }
	internal Boolean IsWaitNotificationEnabled { get; }
	public Int32 Id { get; }
	internal static Task InternalCurrent { get; }
	internal static StackGuard CurrentStackGuard { get; }
	public AggregateException Exception { get; }
	public TaskStatus Status { get; }
	public Boolean IsCanceled { get; }
	internal Boolean IsCancellationRequested { get; }
	internal CancellationToken CancellationToken { get; }
	internal Boolean IsCancellationAcknowledged { get; }
	public Boolean IsCompleted { get; }
	public Boolean IsCompletedSuccessfully { get; }
	public TaskCreationOptions CreationOptions { get; }
	private WaitHandle System.IAsyncResult.AsyncWaitHandle { get; }
	public Object AsyncState { get; }
	private Boolean System.IAsyncResult.CompletedSynchronously { get; }
	internal TaskScheduler ExecutingTaskScheduler { get; }
	public static TaskFactory Factory { get; }
	public static Task CompletedTask { get; }
	internal ManualResetEventSlim CompletedEvent { get; }
	internal Boolean ExceptionRecorded { get; }
	public Boolean IsFaulted { get; }
	internal ExecutionContext CapturedContext { get; set; }
	internal Boolean IsExceptionObservedByParent { get; }
	internal Boolean IsDelegateInvoked { get; }

	// RVA: 0x612c0e4 VA: 0x75987440e4
	internal Void .ctor(Boolean canceled, TaskCreationOptions creationOptions, CancellationToken ct) { }
	// RVA: 0x612c1e0 VA: 0x75987441e0
	internal Void .ctor() { }
	// RVA: 0x612c208 VA: 0x7598744208
	internal Void .ctor(Object state, TaskCreationOptions creationOptions, Boolean promiseStyle) { }
	// RVA: 0x612c4e0 VA: 0x75987444e0
	internal Void .ctor(Delegate action, Object state, Task parent, CancellationToken cancellationToken, TaskCreationOptions creationOptions, InternalTaskOptions internalOptions, TaskScheduler scheduler) { }
	// RVA: 0x612c334 VA: 0x7598744334
	internal Void TaskConstructorCore(Delegate action, Object state, CancellationToken cancellationToken, TaskCreationOptions creationOptions, InternalTaskOptions internalOptions, TaskScheduler scheduler) { }
	// RVA: 0x612c63c VA: 0x759874463c
	private Void AssignCancellationToken(CancellationToken cancellationToken, Task antecedent, TaskContinuation continuation) { }
	// RVA: 0x612cca4 VA: 0x7598744ca4
	private static Void TaskCancelCallback(Object o) { }
	// RVA: 0x612ba38 VA: 0x7598743a38
	internal Boolean TrySetCanceled(CancellationToken tokenToRecord) { }
	// RVA: 0x612b134 VA: 0x7598743134
	internal Boolean TrySetCanceled(CancellationToken tokenToRecord, Object cancellationException) { }
	// RVA: 0x612ba40 VA: 0x7598743a40
	internal Boolean TrySetException(Object exceptionObject) { }
	// RVA: 0x612ca24 VA: 0x7598744a24
	internal TaskCreationOptions get_Options() { }
	// RVA: 0x612d39c VA: 0x759874539c
	internal static TaskCreationOptions OptionsMethod(Int32 flags) { }
	// RVA: 0x612cfe8 VA: 0x7598744fe8
	internal Boolean AtomicStateUpdate(Int32 newBits, Int32 illegalBits) { }
	// RVA: 0x612d3a4 VA: 0x75987453a4
	internal Boolean AtomicStateUpdate(Int32 newBits, Int32 illegalBits, ref Int32 oldFlags) { }
	// RVA: 0x612d478 VA: 0x7598745478
	internal Void SetNotificationForWaitCompletion(Boolean enabled) { }
	// RVA: 0x612d550 VA: 0x7598745550
	internal Boolean NotifyDebuggerOfWaitCompletionIfNecessary() { }
	// RVA: 0x612d5e0 VA: 0x75987455e0
	internal Boolean get_IsWaitNotificationEnabledOrNotRanToCompletion() { }
	// RVA: 0x612d608 VA: 0x7598745608
	internal virtual Boolean get_ShouldNotifyDebuggerOfWaitCompletion() { }
	// RVA: 0x612d5a0 VA: 0x75987455a0
	internal Boolean get_IsWaitNotificationEnabled() { }
	// RVA: 0x612d5b8 VA: 0x75987455b8
	private Void NotifyDebuggerOfWaitCompletion() { }
	// RVA: 0x612d620 VA: 0x7598745620
	internal Boolean MarkStarted() { }
	// RVA: 0x612c5c8 VA: 0x75987445c8
	internal Void AddNewChild() { }
	// RVA: 0x612cc5c VA: 0x7598744c5c
	internal Void DisregardChild() { }
	// RVA: 0x612d62c VA: 0x759874562c
	internal static Task InternalStartNew(Task creatingTask, Delegate action, Object state, CancellationToken cancellationToken, TaskScheduler scheduler, TaskCreationOptions options, InternalTaskOptions internalOptions) { }
	// RVA: 0x612bd8c VA: 0x7598743d8c
	public Int32 get_Id() { }
	// RVA: 0x612d948 VA: 0x7598745948
	internal static Task get_InternalCurrent() { }
	// RVA: 0x612d9a0 VA: 0x75987459a0
	internal static Task InternalCurrentIfAttached(TaskCreationOptions creationOptions) { }
	// RVA: 0x612da3c VA: 0x7598745a3c
	internal static StackGuard get_CurrentStackGuard() { }
	// RVA: 0x612db04 VA: 0x7598745b04
	public AggregateException get_Exception() { }
	// RVA: 0x612dcb0 VA: 0x7598745cb0
	public TaskStatus get_Status() { }
	// RVA: 0x612dd10 VA: 0x7598745d10
	public Boolean get_IsCanceled() { }
	// RVA: 0x612dd30 VA: 0x7598745d30
	internal Boolean get_IsCancellationRequested() { }
	// RVA: 0x612c9e4 VA: 0x75987449e4
	internal ContingentProperties EnsureContingentPropertiesInitialized(Boolean needsProtection) { }
	// RVA: 0x612ddc0 VA: 0x7598745dc0
	private ContingentProperties EnsureContingentPropertiesInitializedCore(Boolean needsProtection) { }
	// RVA: 0x612a4d4 VA: 0x75987424d4
	internal CancellationToken get_CancellationToken() { }
	// RVA: 0x612deac VA: 0x7598745eac
	internal Boolean get_IsCancellationAcknowledged() { }
	// RVA: 0x612a760 VA: 0x7598742760
	public Boolean get_IsCompleted() { }
	// RVA: 0x612dec4 VA: 0x7598745ec4
	private static Boolean IsCompletedMethod(Int32 flags) { }
	// RVA: 0x612ded4 VA: 0x7598745ed4
	public Boolean get_IsCompletedSuccessfully() { }
	// RVA: 0x612c5b4 VA: 0x75987445b4
	public TaskCreationOptions get_CreationOptions() { }
	// RVA: 0x612defc VA: 0x7598745efc
	private WaitHandle System.IAsyncResult.get_AsyncWaitHandle() { }
	// RVA: 0x612e078 VA: 0x7598746078
	public Object get_AsyncState() { }
	// RVA: 0x612e080 VA: 0x7598746080
	private Boolean System.IAsyncResult.get_CompletedSynchronously() { }
	// RVA: 0x612e088 VA: 0x7598746088
	internal TaskScheduler get_ExecutingTaskScheduler() { }
	// RVA: 0x612e090 VA: 0x7598746090
	public static TaskFactory get_Factory() { }
	// RVA: 0x612e0e8 VA: 0x75987460e8
	public static Task get_CompletedTask() { }
	// RVA: 0x612df84 VA: 0x7598745f84
	internal ManualResetEventSlim get_CompletedEvent() { }
	// RVA: 0x612e140 VA: 0x7598746140
	internal Boolean get_ExceptionRecorded() { }
	// RVA: 0x612db40 VA: 0x7598745b40
	public Boolean get_IsFaulted() { }
	// RVA: 0x612e1b0 VA: 0x75987461b0
	internal ExecutionContext get_CapturedContext() { }
	// RVA: 0x612c934 VA: 0x7598744934
	internal Void set_CapturedContext(ExecutionContext value) { }
	// RVA: 0x612e220 VA: 0x7598746220
	public Void Dispose() { }
	// RVA: 0x612e28c VA: 0x759874628c
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x612d738 VA: 0x7598745738
	internal Void ScheduleAndStart(Boolean needsProtection) { }
	// RVA: 0x612d208 VA: 0x7598745208
	internal Void AddException(Object exceptionObject) { }
	// RVA: 0x612e3f4 VA: 0x75987463f4
	internal Void AddException(Object exceptionObject, Boolean representsCancellation) { }
	// RVA: 0x612db58 VA: 0x7598745b58
	private AggregateException GetExceptions(Boolean includeTaskCanceledExceptions) { }
	// RVA: 0x612e7b0 VA: 0x75987467b0
	internal ReadOnlyCollection`1 GetExceptionDispatchInfos() { }
	// RVA: 0x612e948 VA: 0x7598746948
	internal ExceptionDispatchInfo GetCancellationExceptionDispatchInfo() { }
	// RVA: 0x612e978 VA: 0x7598746978
	internal Void ThrowIfExceptional(Boolean includeTaskCanceledExceptions) { }
	// RVA: 0x612e9c0 VA: 0x75987469c0
	internal Void UpdateExceptionObservedStatus() { }
	// RVA: 0x612ea94 VA: 0x7598746a94
	internal Boolean get_IsExceptionObservedByParent() { }
	// RVA: 0x612eaac VA: 0x7598746aac
	internal Boolean get_IsDelegateInvoked() { }
	// RVA: 0x612d210 VA: 0x7598745210
	internal Void Finish(Boolean bUserDelegateExecuted) { }
	// RVA: 0x612eac4 VA: 0x7598746ac4
	internal Void FinishStageTwo() { }
	// RVA: 0x612f2c0 VA: 0x75987472c0
	internal Void FinishStageThree() { }
	// RVA: 0x612f320 VA: 0x7598747320
	internal Void ProcessChildCompletion(Task childTask) { }
	// RVA: 0x612ed3c VA: 0x7598746d3c
	internal Void AddExceptionsFromChildren() { }
	// RVA: 0x612fbc0 VA: 0x7598747bc0
	private Void Execute() { }
	// RVA: 0x612fd74 VA: 0x7598747d74
	private Void System.Threading.IThreadPoolWorkItem.ExecuteWorkItem() { }
	// RVA: 0x612fd7c VA: 0x7598747d7c
	internal Boolean ExecuteEntry(Boolean bPreventDoubleExecution) { }
	// RVA: 0x6130080 VA: 0x7598748080
	private static Void ExecutionContextCallback(Object obj) { }
	// RVA: 0x61300f8 VA: 0x75987480f8
	internal virtual Void InnerInvoke() { }
	// RVA: 0x612fc6c VA: 0x7598747c6c
	private Void HandleException(Exception unhandledException) { }
	// RVA: 0x612aa38 VA: 0x7598742a38
	public TaskAwaiter GetAwaiter() { }
	// RVA: 0x612aa60 VA: 0x7598742a60
	public ConfiguredTaskAwaitable ConfigureAwait(Boolean continueOnCapturedContext) { }
	// RVA: 0x61301d8 VA: 0x75987481d8
	internal Void SetContinuationForAwait(Action continuationAction, Boolean continueOnCapturedContext, Boolean flowExecutionContext) { }
	// RVA: 0x61305f8 VA: 0x75987485f8
	public static YieldAwaitable Yield() { }
	// RVA: 0x6130600 VA: 0x7598748600
	public Void Wait() { }
	// RVA: 0x613060c VA: 0x759874860c
	public Boolean Wait(Int32 millisecondsTimeout, CancellationToken cancellationToken) { }
	// RVA: 0x6130e68 VA: 0x7598748e68
	private Boolean WrappedTryRunInline() { }
	// RVA: 0x6130760 VA: 0x7598748760
	internal Boolean InternalWait(Int32 millisecondsTimeout, CancellationToken cancellationToken) { }
	// RVA: 0x61311cc VA: 0x75987491cc
	private Boolean SpinThenBlockingWait(Int32 millisecondsTimeout, CancellationToken cancellationToken) { }
	// RVA: 0x6131368 VA: 0x7598749368
	private Boolean SpinWait(Int32 millisecondsTimeout) { }
	// RVA: 0x612ca80 VA: 0x7598744a80
	internal Boolean InternalCancel(Boolean bCancelNonExecutingOnly) { }
	// RVA: 0x6131574 VA: 0x7598749574
	internal Void RecordInternalCancellationRequest() { }
	// RVA: 0x61315bc VA: 0x75987495bc
	internal Void RecordInternalCancellationRequest(CancellationToken tokenToRecord) { }
	// RVA: 0x612d0ac VA: 0x75987450ac
	internal Void RecordInternalCancellationRequest(CancellationToken tokenToRecord, Object cancellationException) { }
	// RVA: 0x612d0e8 VA: 0x75987450e8
	internal Void CancellationCleanupLogic() { }
	// RVA: 0x61301ac VA: 0x75987481ac
	private Void SetCancellationAcknowledged() { }
	// RVA: 0x612f4d8 VA: 0x75987474d8
	internal Void FinishContinuations() { }
	// RVA: 0x6131824 VA: 0x7598749824
	private Void LogFinishCompletionNotification() { }
	// RVA: 0x6131878 VA: 0x7598749878
	public Task ContinueWith(Action`1 continuationAction) { }
	// RVA: 0x613198c VA: 0x759874998c
	private Task ContinueWith(Action`1 continuationAction, TaskScheduler scheduler, CancellationToken cancellationToken, TaskContinuationOptions continuationOptions) { }
	// RVA: 0x6131e2c VA: 0x7598749e2c
	public Task ContinueWith(Action`2 continuationAction, Object state, CancellationToken cancellationToken, TaskContinuationOptions continuationOptions, TaskScheduler scheduler) { }
	// RVA: 0x6131e40 VA: 0x7598749e40
	private Task ContinueWith(Action`2 continuationAction, Object state, TaskScheduler scheduler, CancellationToken cancellationToken, TaskContinuationOptions continuationOptions) { }
	// RVA: 0x6131af0 VA: 0x7598749af0
	internal static Void CreationOptionsFromContinuationOptions(TaskContinuationOptions continuationOptions, out TaskCreationOptions creationOptions, out InternalTaskOptions internalOptions) { }
	// RVA: 0x6131cd8 VA: 0x7598749cd8
	internal Void ContinueWithCore(Task continuationTask, TaskScheduler scheduler, CancellationToken cancellationToken, TaskContinuationOptions options) { }
	// RVA: 0x61320f4 VA: 0x759874a0f4
	internal Void AddCompletionAction(ITaskCompletionAction action) { }
	// RVA: 0x61314a0 VA: 0x75987494a0
	private Void AddCompletionAction(ITaskCompletionAction action, Boolean addBeforeOthers) { }
	// RVA: 0x61320fc VA: 0x759874a0fc
	private Boolean AddTaskContinuationComplex(Object tc, Boolean addBeforeOthers) { }
	// RVA: 0x61304fc VA: 0x75987484fc
	private Boolean AddTaskContinuation(Object tc, Boolean addBeforeOthers) { }
	// RVA: 0x612cd94 VA: 0x7598744d94
	internal Void RemoveContinuation(Object continuationObject) { }
	// RVA: 0x VA: 0x0
	public static Task`1 FromResult(TResult result) { }
	// RVA: 0x612b188 VA: 0x7598743188
	public static Task FromException(Exception exception) { }
	// RVA: 0x VA: 0x0
	public static Task`1 FromException(Exception exception) { }
	// RVA: 0x613241c VA: 0x759874a41c
	internal static Task FromCancellation(CancellationToken cancellationToken) { }
	// RVA: 0x612b5ec VA: 0x75987435ec
	public static Task FromCanceled(CancellationToken cancellationToken) { }
	// RVA: 0x VA: 0x0
	internal static Task`1 FromCancellation(CancellationToken cancellationToken) { }
	// RVA: 0x VA: 0x0
	public static Task`1 FromCanceled(CancellationToken cancellationToken) { }
	// RVA: 0x VA: 0x0
	internal static Task`1 FromCancellation(OperationCanceledException exception) { }
	// RVA: 0x6132508 VA: 0x759874a508
	public static Task Run(Action action) { }
	// RVA: 0x VA: 0x0
	public static Task`1 Run(Func`1 function) { }
	// RVA: 0x61325d8 VA: 0x759874a5d8
	public static Task Run(Func`1 function) { }
	// RVA: 0x6132630 VA: 0x759874a630
	public static Task Run(Func`1 function, CancellationToken cancellationToken) { }
	// RVA: 0x VA: 0x0
	public static Task`1 Run(Func`1 function) { }
	// RVA: 0x VA: 0x0
	public static Task`1 Run(Func`1 function, CancellationToken cancellationToken) { }
	// RVA: 0x6132864 VA: 0x759874a864
	public static Task Delay(Int32 millisecondsDelay) { }
	// RVA: 0x61328bc VA: 0x759874a8bc
	public static Task Delay(Int32 millisecondsDelay, CancellationToken cancellationToken) { }
	// RVA: 0x6132d88 VA: 0x759874ad88
	public static Task`1 WhenAny(Task[] tasks) { }
	// RVA: 0x6133164 VA: 0x759874b164
	public static Task`1 WhenAny(IEnumerable`1 tasks) { }
	// RVA: 0x61335e0 VA: 0x759874b5e0
	internal static Boolean AddToActiveTasks(Task task) { }
	// RVA: 0x6133744 VA: 0x759874b744
	internal static Void RemoveFromActiveTasks(Int32 taskId) { }
	// RVA: 0x6133888 VA: 0x759874b888
	public Void MarkAborted(ThreadAbortException e) { }
	// RVA: 0x612fe98 VA: 0x7598747e98
	private Void ExecuteWithThreadLocal(ref Task currentTaskSlot) { }
	// RVA: 0x6133898 VA: 0x759874b898
	private static Void .cctor() { }
}
```