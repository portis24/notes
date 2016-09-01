coherence stalls or latency tolerance - Informed CPU scheduling for socket and core sharing
SMiTe: Precise QoS Prediction on Real-System SMT Processors to Improve Utilization in Warehouse Scale Computers
Bubble-Flux: Precise Online QoS Management for
Increased Utilization in Warehouse Scale Computers

cloudsuite faban

IO Performance Interference among Consolidated n-Tier Applications: Sharing is Better than Isolation for Disks
An Analysis of Performance Interference Effects in Virtual Environments
Modeling I/O Interference for Data Intensive Distributed Applications
Bubble-Up: Increasing Utilization in Modern Warehouse Scale Computers via Sensible Co-locations
Heracles: Improving Resource Efficiency at Scale
The Impact of Memory Subsystem Resource Sharing on Datacenter Applications
QUALITY-OF-SERVICE-AWARE SCHEDULING IN HETEROGENEOUS DATACENTERS WITH PARAGON
CPU Caches and Why You Care
iBench: Quantifying Interference for Datacenter Applications
Bubble-Flux: Precise Online QoS Management forIncreased Utilization in Warehouse Scale Computers



git diff ef773f9 --stat

MODIFIED & ADDED:

pkg/api/register.go
pkg/api/types.go
pkg/api/v1/register.go
pkg/api/v1/types.go
pkg/api/validation/validation.go

pkg/client/cache/listers.go
pkg/client/unversioned/client.go
pkg/client/unversioned/profiles.go
pkg/client/unversioned/profiles_test.go
pkg/client/unversioned/testclient/fake_profiles.go
pkg/client/unversioned/testclient/testclient.go
pkg/kubectl/cmd/cmd.go
pkg/kubectl/kubectl.go
pkg/kubectl/resource_printer.go
pkg/master/master.go
pkg/registry/cachesize/cachesize.go

pkg/registry/profile/etcd/etcd.go
pkg/registry/profile/etcd/etcd_test.go
pkg/registry/profile/registry.go
pkg/registry/profile/strategy.go
pkg/registry/profile/strategy_test.go


多任务调度框架

git show 94bb2989

cmd/integration/integration.go
cmd/kube-controller-manager/app/controllermanager.go
api/install/install.go
pkg/api/register.go
pkg/api/types.go
pkg/api/v1/register.go
pkg/api/v1/types.go
pkg/api/validation/validation.go

pkg/apis/batch/v1/conversion.go
pkg/apis/componentconfig/types.go
pkg/apis/extensions/v1beta1/conversion.go

pkg/client/cache/listers.go
pkg/client/unversioned/client.go
pkg/client/unversioned/scheduler.go
pkg/client/unversioned/testclient/fake_schedulers.go
pkg/client/unversioned/testclient/testclient.go
pkg/controller/controller_utils.go
pkg/controller/scheduler/scheduler_controller.go
pkg/master/master.go
pkg/registry/cachesize/cachesize.go
pkg/registry/scheduler/etcd/etcd.go
pkg/registry/scheduler/registry.go
pkg/registry/scheduler/strategy.go
pkg/util/heaps/heap.go
pkg/util/heaps/heap_test.go
pkg/util/httpstream/spdy/roundtripper_test.go
plugin/cmd/kube-scheduler/app/options/options.go
plugin/cmd/kube-scheduler/app/server.go
plugin/pkg/scheduler/algorithm/priorities/priorities.go
plugin/pkg/scheduler/factory/factory.go 
plugin/pkg/scheduler/factory/factory_test.go
plugin/pkg/scheduler/scheduler.go
plugin/pkg/scheduler/scheduler_test.go
