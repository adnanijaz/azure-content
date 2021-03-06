<properties
	pageTitle="Service Bus Messaging overview - Azure"
	description="Service Bus Messaging: Flexible Data Delivery in the Cloud"
	services="service-bus"
	documentationCenter=".net"
	authors="djrosanova"
	manager="timlt"
	editor="mattshel"/>

<tags
	ms.service="service-bus"
	ms.workload="tbd"
	ms.tgt_pltfrm="na"
	ms.devlang="multiple"
	ms.topic="article"
	ms.date="02/20/2015"
	ms.author="sethm"/>


# Service Bus Messaging: Flexible Data Delivery in the Cloud

Azure Service Bus messaging is a reliable information delivery service. The purpose of this service is to make communication easier. When two or more parties want to exchange information they need a communication mechanism. Azure messaging is a brokered, or third party communication mechanism. This is similar to a postal service in the physical world. Postal services make it very easy to send a variety of letters and packages with a variety of delivery guarantees anywhere in the world.

Like the postal service delivering letters Azure Service Bus messaging is about flexible information delivery from both the sender and the recipient. The messaging service will ensure that the information is delivered even if the two parties are never both online at the same time, or if they aren't available at the exact same instance. In this way messaging is like sending a letter while non-brokered communication is like placing a phone call (or how a phone call used to be - before call waiting and caller ID, which are much more like brokered messaging).

The message sender can also require a variety of delivery characteristics including transactions, duplicate detection, time based expiration, and batching. These largely have postal analogies as well like repeat delivery, required signature, address change or recall.

Azure Service Bus messaging has two separate features: Queues and Topics. Both support all of the concepts presented above - and more - the primary difference is that Topics support Publish-Subscribe capabilities that be used for sophisticated content based routing and delivery logic including sending to multiple recipients.

For more about Service Bus Messaging

[Azure Service Bus Architectural Overview](fundamentals-service-bus-hybrid-solutions/)

[How to use Service Bus Queues](service-bus-dotnet-how-to-use-queues)

[How to use Service Bus Topics](service-bus-dotnet-how-to-use-topics-subscriptions)
