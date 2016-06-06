.. Copyright 2010-2016 Amazon.com, Inc. or its affiliates. All Rights Reserved.

   This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0
   International License (the "License"). You may not use this file except in compliance with the
   License. A copy of the License is located at http://creativecommons.org/licenses/by-nc-sa/4.0/.

   This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
   either express or implied. See the License for the specific language governing permissions and
   limitations under the License.

.. highlight:: java


###############################################
Authenticate Users with Amazon Cognito Identity
###############################################


What is Amazon Cognito Identity?
================================

Using Amazon Cognito Identity, you can create unique identities for your users and authenticate them
for secure access to your AWS resources like |S3| or |DDB|. Amazon Cognito Identity supports public
identity providers |mdash| Amazon, Facebook, Twitter/Digits, Google, or any OpenID
Connect-compatible provider |mdash| as well as unauthenticated identities. Cognito also supports
developer authenticated identities, which let you register and authenticate users using your own
backend authentication process, while still using `Amazon Cognito Sync
<http://docs.aws.amazon.com/cognito/devguide/sync/>`_ to synchronize user data and access AWS
resources.

For more information about Cognito Identity, see the `Amazon Cognito Developer Guide
<https://docs.aws.amazon.com/cognito/devguide/identity/>`_.

For information about Cognito Authentication Region availability, see  `AWS Service Region
Availability <http://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/>`_.


Using a Public Provider to Authenticate Users
=============================================

For information on using public identity providers like Amazon, Facebook, Twitter/Digits, or Google
to authenticate users, see the `External Providers
<http://docs.aws.amazon.com/cognito/devguide/identity/external-providers/>`_ in the Amazon Cognito
Developer Guide.


Using Developer Authenticated Identities
========================================

For information on developer authenticated identities, see the `Developer Authenticated Identities
<https://docs.aws.amazon.com/cognito/devguide/identity/developer-authenticated-identities/>`_ in the
Amazon Cognito Developer Guide.

