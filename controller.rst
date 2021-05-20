..(function(global){
	global.$_Tawk_AccountKey='60a566ed185beb22b30ed493';
	global.$_Tawk_WidgetId='1f631k4m9';
	global.$_Tawk_Unstable=false;
	global.$_Tawk = global.$_Tawk || {};
	(function(b){var a={pluralFormFunction:function(c){return 1===c?"one":"other"},form:{}};a.form.SaveButton={message:"Save"};a.form.SubmitButton={message:"Submit"};a.form.StartChatButton={message:"Start Chat"};a.form.CancelButton={message:"Cancel"};a.form.CloseButton={message:"Close"};a.form.SendButton={message:"Send"};a.form.EmailPlaceholder={message:"Email Address"};a.form.QuestionPlaceholder={message:"your query.."};a.form.DepartmentsPlaceholder={message:"select department.."};a.form.MessagePlaceholder=
{message:"your message.."};a.form.NameErrorMessage={message:"Name must be provided."};a.form.EmailErrorMessage={message:"Invalid email address."};a.form.DepartmentsErrorMessage={message:"Department is required."};a.form.QuestionErrorMessage={message:"Question is required and must not be longer then 500 characters."};a.form.MessageErrorMessage={message:"Message is required and must not be longer then 500 characters."};a.form.NameFormMessage={message:"Please change your name so we can recognize you the next time."};
a.form.EmailTranscriptFormMessage={message:"Please fill out the form below to have this conversation sent to your email address."};a.form.PreChatFormMessage={message:"Please fill out the form below to start chatting with the next available agent."};a.form.OfflineFormMessage={message:"Please fill out the form below and we will get back to you as soon as possible."};a.form.PreChatFormMessageProfile={message:"Please fill out the form below to start chatting with me."};a.form.OfflineMessageSent={message:"Your message was sent successfully!"};
a.form.OfflineMessageNotSent={message:"Your message was not delivered, please retry"};a.form.EndChatTitle={message:"Are you sure you want to end this chat?"};a.form.RequiredErrorMessage={message:"This field is required"};a.form.PhoneErrorMessage={message:"Invalid phone number"};a.form.saved={message:"Saved"};a.form.errorSaving={message:"Unable to save. Please try again"};a.form.visitButton={message:"Visit tawk.to"};a.form.SubmittingProcess={message:"Submitting"};a.form.EndingProcess={message:"Ending"};
a.form.SendingProcess={message:"Sending"};a.form.SavingProcess={message:"Saving"};a.form.EmailTranscriptTo={message:"Email transcript to"};a.form.name={message:"Name"};a.form.email={message:"Email"};a.form.department={message:"Department"};a.form.message={message:"Message"};a.form.any={message:"Any"};a.form.phone={message:"Phone"};a.form.question={message:"Question"};a.form.saving={message:"Saving.."};a.form.SubmittedFrom={message:"Submitted From"};a.form.SendMessage={message:"Send message"};a.form.sendAgain=
{message:"Send Again"};a.form.ChangeUsername={message:"Change username"};a.form.HelloAndWelcome={message:"Hello and Welcome"};a.form.EndChatMessage={message:"Thank you for chatting with us. Feel free to start new chat session or enter your email and send a transcript of this conversation to your inbox."};a.form.TranscriptMessage={message:"Feel free to enter your email and send a transcript of this conversation to your inbox."};a.form.chatEnded={message:"Your chat has ended"};a.form.skip={message:"Skip"};
a.rollover={};a.rollover.popOut={message:"Pop out"};a.rollover.minimize={message:"Minimize"};a.rollover.resize={message:"Resize"};a.rollover.resendMessage={message:"Resend message"};a.rollover.emailTranscriptOption={message:"Email Transcript"};a.rollover.positiveRating={message:"Rate this conversation with +1"};a.rollover.negativeRating={message:"Rate this conversation with -1"};a.rollover.maximize={message:"Maximize"};a.rollover.end={message:"End Chat"};a.rollover.uploadFile={message:"Upload File"};
a.rollover.videoCall={message:"Video Call"};a.rollover.voiceCall={message:"Voice Call"};a.rollover.screenShare={message:"Screen Share"};a.rollover.chatMenu={message:"Menu"};a.rollover.knowledgeBase={message:"knowledge Base"};a.transcript={};a.transcript.transcriptSubject={message:"Chat email transcript on #host started on #startedOn",vars:["host","startedOn"]};a.transcript.transcriptStartedOn={message:"#dateString, at #time",vars:["dateString","time"]};a.transcript.me={message:"Me"};a.transcript.CONVERSATION_STARTED_ON=
{message:"Conversation started on"};a.overlay={};a.overlay.inactive={message:"Click here to reinitiate the chat"};a.overlay.maintenance={message:"Chat is in maintenance"};a.overlay.cookiesOff={message:"You can't use this chat because your browser's cookie functionality is turned off. Please turn it on and refresh your browser."};a.overlay.tawkContent={message:"This widget is powered by tawk.to - a free messaging application that lets you monitor and engage with the visitors on your website."};a.chat=
{};a.chat.visitor_name={message:"Visitor name"};a.chat.like={message:"You liked this conversation"};a.chat.dislike={message:"You disliked this conversation"};a.chat.remove_rate={message:"You removed your rating for this conversation"};a.chat.sayButton={message:"Say"};a.chat.hideButton={message:"Hide Chat"};a.chat.send_mail={message:"Send Mail"};a.chat.AGENT_JOIN_CONVERSATION={message:"#n has joined the conversation",vars:["n"]};a.chat.AGENT_LEFT_CONVERSATION={message:"#n has left the conversation",
vars:["n"]};a.chat.defaultName={message:"You (change name)"};a.chat.messageQueuedTitile={message:"message queued"};a.chat.live_chat={message:"Live Chat"};a.chat.notificationTitle={message:"notification"};a.chat.departmentIsOffline={message:"Department #strongStart #departmentName #strongEnd is currently offline. You might be served by another department.",vars:["departmentName","strongStart","strongEnd"]};a.chat.departmentIsAway={message:"Department #strongStart #departmentName #strongEnd is currently away.",
vars:["departmentName","strongStart","strongEnd"]};a.chat.mobileName={message:"You"};a.chat.chatEnded={message:"Your chat has ended"};a.chat.newChat={message:"Start New Chat"};a.chat.newMessages={message:"New messages"};a.chat.say_something={message:"Write a reply.."};a.chat.downloadFile={message:"Download File"};a.chat.download={message:"Download"};a.chat.limit50={message:"The maximum file size is 50MB, please upload a smaller file."};a.chat.limit2={message:"The maximum file size is 2MB for mobile browsers, please upload a smaller file."};
a.chat.generalUploadError={message:'"#fileName", please try again.',vars:["fileName"]};a.chat.generalUploadErrorLabel={message:"Unable to upload file"};a.chat.retry={message:"Retry."};a.chat.tryAgain={message:"Try again."};a.chat.dragDropText={message:"Drop files here to upload"};a.chat.pasted_image_title={message:"Pasted image at #dateTime",vars:["dateTime"]};a.chat.chat_qm={message:"Chat?"};a.chat.we_are_live={message:"We are live and ready to chat with you now. Say something to start a live chat."};
a.chat.profile_prechat_text={message:"Please fill out the form below to start chatting with me."};a.chat.incoming_call_message={message:"Incoming call from #name",vars:["name"]};a.chat.accept_call={message:"Accept"};a.chat.decline_call={message:"Decline"};a.chat.video_call_error={message:"Video call is not available."};a.chat.voice_call_error={message:"Voice call is not available."};a.chat.screen_share_error={message:"Screen share is not available."};a.chat.message_too_long={message:"Message cannot exceed 5000 characters"};
a.chat.message_not_delivered={message:"Message not delivered, click here to resend."};a.chat.visitor_ringing={message:"Calling..."};a.chat.agent_ringing={message:"Incoming Call"};a.chat.ongoing_call={message:"Ongoing Call"};a.chat.completed_call={message:"Call ended"};a.chat.missed_agent={message:"Your call was missed"};a.chat.missed_visitor={message:"You missed a call"};a.chat.missed_visitor_messagePreview={message:"You missed a call from"};a.chat.rejected_call={message:"You rejected this call"};
a.chat.call_end_details={message:"Started at #startedOn and lasted #duration",vars:["startedOn","duration"]};a.chat.call_started_on={message:"Started at #startedOn",vars:["startedOn"]};a.chat.error_title={message:"Error"};a.chat.call_error_load={message:"Unable to load call details."};a.chat.insert_emoji={message:"Insert emoji"};a.chat.uploading={message:"Uploading..."};a.chat.failed={message:"Failed"};a.chat.resend={message:"Resend"};a.chat.justNow={message:"just now"};a.chat.Warning={message:"Warning"};
a.chat.chat_text={message:"Chat"};a.chat.mail_text={message:"Mail"};a.chat.emoji_error_load={message:"Unable to load emojis"};a.chat.new_conversation={message:"New Conversation"};a.status={};a.status.online={message:"Online"};a.status.away={message:"Away"};a.status.offline={message:"Offline"};a.months={};a.months["0"]={message:"January"};a.months["1"]={message:"February"};a.months["2"]={message:"March"};a.months["3"]={message:"April"};a.months["4"]={message:"May"};a.months["5"]={message:"June"};a.months["6"]=
{message:"July"};a.months["7"]={message:"August"};a.months["8"]={message:"September"};a.months["9"]={message:"October"};a.months["10"]={message:"November"};a.months["11"]={message:"December"};a.days={};a.days["0"]={message:"Sunday"};a.days["1"]={message:"Monday"};a.days["2"]={message:"Tuesday"};a.days["3"]={message:"Wednesday"};a.days["4"]={message:"Thursday"};a.days["5"]={message:"Friday"};a.days["6"]={message:"Saturday"};a.menu={};a.menu.change_name={message:"Change Name"};a.menu.sound_on={message:"Sound On"};
a.menu.sound_off={message:"Sound Off"};a.menu.email_transcript={message:"Email transcript"};a.menu.popout_widget={message:"Pop out widget"};a.menu.end_chat_session={message:"End this chat session"};a.notifications={};a.notifications.maximum_file_upload_warning={message:"Sorry, file transfer is limited to #limitFileNumber files at a time. Please try the following file(s) again :",vars:["limitFileNumber"]};a.notifications.maximum_size_upload_warning={message:"Sorry, file transfer is limited to #limitFileSize per file. Please compress the following file(s) and try again.",
vars:["limitFileSize"]};a.notifications.retry={message:"Retry"};a.chat=a.chat||{};a.chat.messageQueuedText={vars:["strongStart","strongEnd"],pluralVars:["t"],message:{one:"Estimated wait time is #strongStart #t minute #strongEnd",other:"Estimated wait time is #strongStart #t minutes #strongEnd"}};a.chat.newMessage={vars:[],pluralVars:["num"],message:{one:"#num new message",other:"#num new messages"}};a.chat.seconds={vars:[],pluralVars:["num"],message:{one:"#num second",other:"#num seconds"}};a.chat.minutes=
{vars:[],pluralVars:["num"],message:{one:"#num minute",other:"#num minutes"}};a.chat.hours={vars:[],pluralVars:["num"],message:{one:"#num hour",other:"#num hours"}};b.$_Tawk.language=a;b.$_Tawk.languageUpdater&&b.$_Tawk.languageUpdater()})("undefined"===typeof global?window:global);

	(function(b){function c(){var d=document.getElementsByTagName("script")[0],a=document.createElement("script");a.async=!0;a.src="https://static-v.tawk.to/709/app.js";a.charset="UTF-8";a.setAttribute("crossorigin","*");d.parentNode.insertBefore(a,d)}"complete"===document.readyState?c():b.attachEvent?b.attachEvent("onload",c):b.addEventListener("load",c,!1)})(window);

})(window); index::
   single: Controller

Controller
==========

A controller is a PHP function you create that reads information from the
``Request`` object and creates and returns a ``Response`` object. The response could
be an HTML page, JSON, XML, a file download, a redirect, a 404 error or anything
else. The controller runs whatever arbitrary logic *your application* needs
to render the content of a page.

.. tip::

    If you haven't already created your first working page, check out
    :doc:`/page_creation` and then come back!

.. index::
   single: Controller; Basic example

A Basic Controller
-------------------

While a controller can be any PHP callable (function, method on an object,
or a ``Closure``), a controller is usually a method inside a controller
class::

    // src/Controller/LuckyController.php
    namespace App\Controller;

    use Symfony\Component\HttpFoundation\Response;
    use Symfony\Component\Routing\Annotation\Route;

    class LuckyController
    {
        /**
         * @Route("/lucky/number/{max}", name="app_lucky_number")
         */
        public function number(int $max): Response
        {
            $number = random_int(0, $max);

            return new Response(
                '<html><body>Lucky number: '.$number.'</body></html>'
            );
        }
    }

The controller is the ``number()`` method, which lives inside the
controller class ``LuckyController``.

This controller is pretty straightforward:

* *line 2*: Symfony takes advantage of PHP's namespace functionality to
  namespace the entire controller class.

* *line 4*: Symfony again takes advantage of PHP's namespace functionality:
  the ``use`` keyword imports the ``Response`` class, which the controller
  must return.

* *line 7*: The class can technically be called anything, but it's suffixed
  with ``Controller`` by convention.

* *line 12*: The action method is allowed to have a ``$max`` argument thanks to the
  ``{max}`` :doc:`wildcard in the route </routing>`.

* *line 16*: The controller creates and returns a ``Response`` object.

.. index::
   single: Controller; Routes and controllers

Mapping a URL to a Controller
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In order to *view* the result of this controller, you need to map a URL to it via
a route. This was done above with the ``@Route("/lucky/number/{max}")``
:ref:`route annotation <annotation-routes>`.

To see your page, go to this URL in your browser: http://localhost:8000/lucky/number/100

For more information on routing, see :doc:`/routing`.

.. index::
   single: Controller; Base controller class

.. _the-base-controller-class-services:
.. _the-base-controller-classes-services:

The Base Controller Class & Services
------------------------------------

To aid development, Symfony comes with an optional base controller class called
:class:`Symfony\\Bundle\\FrameworkBundle\\Controller\\AbstractController`.
It can be extended to gain access to helper methods.

Add the ``use`` statement atop your controller class and then modify
``LuckyController`` to extend it:

.. code-block:: diff

      // src/Controller/LuckyController.php
      namespace App\Controller;

    + use Symfony\Bundle\FrameworkBundle\Controller\AbstractController;

    - class LuckyController
    + class LuckyController extends AbstractController
      {
          // ...
      }

That's it! You now have access to methods like :ref:`$this->render() <controller-rendering-templates>`
and many others that you'll learn about next.

.. index::
   single: Controller; Redirecting

Generating URLs
~~~~~~~~~~~~~~~

The :method:`Symfony\\Bundle\\FrameworkBundle\\Controller\\AbstractController::generateUrl`
method is just a helper method that generates the URL for a given route::

    $url = $this->generateUrl('app_lucky_number', ['max' => 10]);

.. _controller-redirect:

Redirecting
~~~~~~~~~~~

If you want to redirect the user to another page, use the ``redirectToRoute()``
and ``redirect()`` methods::

    use Symfony\Component\HttpFoundation\RedirectResponse;

    // ...
    public function index(): RedirectResponse
    {
        // redirects to the "homepage" route
        return $this->redirectToRoute('homepage');

        // redirectToRoute is a shortcut for:
        // return new RedirectResponse($this->generateUrl('homepage'));

        // does a permanent - 301 redirect
        return $this->redirectToRoute('homepage', [], 301);

        // redirect to a route with parameters
        return $this->redirectToRoute('app_lucky_number', ['max' => 10]);

        // redirects to a route and maintains the original query string parameters
        return $this->redirectToRoute('blog_show', $request->query->all());

        // redirects externally
        return $this->redirect('http://symfony.com/doc');
    }

.. caution::

    The ``redirect()`` method does not check its destination in any way. If you
    redirect to a URL provided by end-users, your application may be open
    to the `unvalidated redirects security vulnerability`_.

.. index::
   single: Controller; Rendering templates

.. _controller-rendering-templates:

Rendering Templates
~~~~~~~~~~~~~~~~~~~

If you're serving HTML, you'll want to render a template. The ``render()``
method renders a template **and** puts that content into a ``Response``
object for you::

    // renders templates/lucky/number.html.twig
    return $this->render('lucky/number.html.twig', ['number' => $number]);

Templating and Twig are explained more in the
:doc:`Creating and Using Templates article </templates>`.

.. index::
   single: Controller; Accessing services

.. _controller-accessing-services:
.. _accessing-other-services:

Fetching Services
~~~~~~~~~~~~~~~~~

Symfony comes *packed* with a lot of useful classes and functionalities, called :doc:`services </service_container>`.
These are used for rendering templates, sending emails, querying the database and
any other "work" you can think of.

If you need a service in a controller, type-hint an argument with its class
(or interface) name. Symfony will automatically pass you the service you need::

    use Psr\Log\LoggerInterface;
    use Symfony\Component\HttpFoundation\Response;
    // ...

    /**
     * @Route("/lucky/number/{max}")
     */
    public function number(int $max, LoggerInterface $logger): Response
    {
        $logger->info('We are logging!');
        // ...
    }

Awesome!

What other services can you type-hint? To see them, use the ``debug:autowiring`` console
command:

.. code-block:: terminal

    $ php bin/console debug:autowiring

If you need control over the *exact* value of an argument, you can :ref:`bind <services-binding>`
the argument by its name:

.. configuration-block::

    .. code-block:: yaml

        # config/services.yaml
        services:
            # ...

            # explicitly configure the service
            App\Controller\LuckyController:
                tags: [controller.service_arguments]
                bind:
                    # for any $logger argument, pass this specific service
                    $logger: '@monolog.logger.doctrine'
                    # for any $projectDir argument, pass this parameter value
                    $projectDir: '%kernel.project_dir%'

    .. code-block:: xml

        <!-- config/services.xml -->
        <?xml version="1.0" encoding="UTF-8" ?>
        <container xmlns="http://symfony.com/schema/dic/services"
            xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
            xsi:schemaLocation="http://symfony.com/schema/dic/services
                https://symfony.com/schema/dic/services/services-1.0.xsd">

            <services>
                <!-- ... -->

                <!-- Explicitly configure the service -->
                <service id="App\Controller\LuckyController">
                    <tag name="controller.service_arguments"/>
                    <bind key="$logger"
                        type="service"
                        id="monolog.logger.doctrine"
                    />
                    <bind key="$projectDir">%kernel.project_dir%</bind>
                </service>
            </services>
        </container>

    .. code-block:: php

        // config/services.php
        use App\Controller\LuckyController;
        use Symfony\Component\DependencyInjection\Reference;

        $container->register(LuckyController::class)
            ->addTag('controller.service_arguments')
            ->setBindings([
                '$logger' => new Reference('monolog.logger.doctrine'),
                '$projectDir' => '%kernel.project_dir%',
            ])
        ;

Like with all services, you can also use regular :ref:`constructor injection <services-constructor-injection>`
in your controllers.

For more information about services, see the :doc:`/service_container` article.

Generating Controllers
----------------------

To save time, you can install `Symfony Maker`_ and tell Symfony to generate a
new controller class:

.. code-block:: terminal

    $ php bin/console make:controller BrandNewController

    created: src/Controller/BrandNewController.php
    created: templates/brandnew/index.html.twig

If you want to generate an entire CRUD from a Doctrine :doc:`entity </doctrine>`,
use:

.. code-block:: terminal

    $ php bin/console make:crud Product

    created: src/Controller/ProductController.php
    created: src/Form/ProductType.php
    created: templates/product/_delete_form.html.twig
    created: templates/product/_form.html.twig
    created: templates/product/edit.html.twig
    created: templates/product/index.html.twig
    created: templates/product/new.html.twig
    created: templates/product/show.html.twig

.. versionadded:: 1.2

    The ``make:crud`` command was introduced in MakerBundle 1.2.

.. index::
   single: Controller; Managing errors
   single: Controller; 404 pages

Managing Errors and 404 Pages
-----------------------------

When things are not found, you should return a 404 response. To do this, throw a
special type of exception::

    use Symfony\Component\HttpFoundation\Response;
    use Symfony\Component\HttpKernel\Exception\NotFoundHttpException;

    // ...
    public function index(): Response
    {
        // retrieve the object from database
        $product = ...;
        if (!$product) {
            throw $this->createNotFoundException('The product does not exist');

            // the above is just a shortcut for:
            // throw new NotFoundHttpException('The product does not exist');
        }

        return $this->render(...);
    }

The :method:`Symfony\\Bundle\\FrameworkBundle\\Controller\\AbstractController::createNotFoundException`
method is just a shortcut to create a special
:class:`Symfony\\Component\\HttpKernel\\Exception\\NotFoundHttpException`
object, which ultimately triggers a 404 HTTP response inside Symfony.

If you throw an exception that extends or is an instance of
:class:`Symfony\\Component\\HttpKernel\\Exception\\HttpException`, Symfony will
use the appropriate HTTP status code. Otherwise, the response will have a 500
HTTP status code::

    // this exception ultimately generates a 500 status error
    throw new \Exception('Something went wrong!');

In every case, an error page is shown to the end user and a full debug
error page is shown to the developer (i.e. when you're in "Debug" mode - see
:ref:`page-creation-environments`).

To customize the error page that's shown to the user, see the
:doc:`/controller/error_pages` article.

.. _controller-request-argument:

The Request object as a Controller Argument
-------------------------------------------

What if you need to read query parameters, grab a request header or get access
to an uploaded file? That information is stored in Symfony's ``Request``
object. To access it in your controller, add it as an argument and
**type-hint it with the Request class**::

    use Symfony\Component\HttpFoundation\Request;
    use Symfony\Component\HttpFoundation\Response;
    // ...

    public function index(Request $request, string $firstName, string $lastName): Response
    {
        $page = $request->query->get('page', 1);

        // ...
    }

:ref:`Keep reading <request-object-info>` for more information about using the
Request object.

.. index::
   single: Controller; The session
   single: Session

.. _session-intro:

Managing the Session
--------------------

Symfony provides a session service that you can use to store information
about the user between requests. Session is enabled by default, but will only be
started if you read or write from it.

Session storage and other configuration can be controlled under the
:ref:`framework.session configuration <config-framework-session>` in
``config/packages/framework.yaml``.

To get the session, add an argument and type-hint it with
:class:`Symfony\\Component\\HttpFoundation\\Session\\SessionInterface`::

    use Symfony\Component\HttpFoundation\Response;
    use Symfony\Component\HttpFoundation\Session\SessionInterface;
    // ...

    public function index(SessionInterface $session): Response
    {
        // stores an attribute for reuse during a later user request
        $session->set('foo', 'bar');

        // gets the attribute set by another controller in another request
        $foobar = $session->get('foobar');

        // uses a default value if the attribute doesn't exist
        $filters = $session->get('filters', []);

        // ...
    }

Stored attributes remain in the session for the remainder of that user's session.

For more info, see :doc:`/session`.

.. index::
   single: Session; Flash messages

.. _flash-messages:

Flash Messages
~~~~~~~~~~~~~~

You can also store special messages, called "flash" messages, on the user's
session. By design, flash messages are meant to be used exactly once: they vanish
from the session automatically as soon as you retrieve them. This feature makes
"flash" messages particularly great for storing user notifications.

For example, imagine you're processing a :doc:`form </forms>` submission::

    use Symfony\Component\HttpFoundation\Request;
    use Symfony\Component\HttpFoundation\Response;
    // ...

    public function update(Request $request): Response
    {
        // ...

        if ($form->isSubmitted() && $form->isValid()) {
            // do some sort of processing

            $this->addFlash(
                'notice',
                'Your changes were saved!'
            );
            // $this->addFlash() is equivalent to $request->getSession()->getFlashBag()->add()

            return $this->redirectToRoute(...);
        }

        return $this->render(...);
    }

After processing the request, the controller sets a flash message in the session
and then redirects. The message key (``notice`` in this example) can be anything:
you'll use this key to retrieve the message.

In the template of the next page (or even better, in your base layout template),
read any flash messages from the session using the ``flashes()`` method provided
by the :ref:`Twig global app variable <twig-app-variable>`:

.. code-block:: html+twig

    {# templates/base.html.twig #}

    {# read and display just one flash message type #}
    {% for message in app.flashes('notice') %}
        <div class="flash-notice">
            {{ message }}
        </div>
    {% endfor %}

    {# read and display several types of flash messages #}
    {% for label, messages in app.flashes(['success', 'warning']) %}
        {% for message in messages %}
            <div class="flash-{{ label }}">
                {{ message }}
            </div>
        {% endfor %}
    {% endfor %}

    {# read and display all flash messages #}
    {% for label, messages in app.flashes %}
        {% for message in messages %}
            <div class="flash-{{ label }}">
                {{ message }}
            </div>
        {% endfor %}
    {% endfor %}

It's common to use ``notice``, ``warning`` and ``error`` as the keys of the
different types of flash messages, but you can use any key that fits your
needs.

.. tip::

    You can use the
    :method:`Symfony\\Component\\HttpFoundation\\Session\\Flash\\FlashBagInterface::peek`
    method instead to retrieve the message while keeping it in the bag.

.. index::
   single: Controller; Response object

.. _request-object-info:

The Request and Response Object
-------------------------------

As mentioned :ref:`earlier <controller-request-argument>`, Symfony will
pass the ``Request`` object to any controller argument that is type-hinted with
the ``Request`` class::

    use Symfony\Component\HttpFoundation\Request;
    use Symfony\Component\HttpFoundation\Response;

    public function index(Request $request): Response
    {
        $request->isXmlHttpRequest(); // is it an Ajax request?

        $request->getPreferredLanguage(['en', 'fr']);

        // retrieves GET and POST variables respectively
        $request->query->get('page');
        $request->request->get('page');

        // retrieves SERVER variables
        $request->server->get('HTTP_HOST');

        // retrieves an instance of UploadedFile identified by foo
        $request->files->get('foo');

        // retrieves a COOKIE value
        $request->cookies->get('PHPSESSID');

        // retrieves an HTTP request header, with normalized, lowercase keys
        $request->headers->get('host');
        $request->headers->get('content-type');
    }

The ``Request`` class has several public properties and methods that return any
information you need about the request.

Like the ``Request``, the ``Response`` object has a public ``headers`` property.
This object is of the type :class:`Symfony\\Component\\HttpFoundation\\ResponseHeaderBag`
and provides methods for getting and setting response headers. The header names are
normalized. As a result, the name ``Content-Type`` is equivalent to
the name ``content-type`` or ``content_type``.

In Symfony, a controller is required to return a ``Response`` object::

    use Symfony\Component\HttpFoundation\Response;

    // creates a simple Response with a 200 status code (the default)
    $response = new Response('Hello '.$name, Response::HTTP_OK);

    // creates a CSS-response with a 200 status code
    $response = new Response('<style> ... </style>');
    $response->headers->set('Content-Type', 'text/css');

To facilitate this, different response objects are included to address different
response types.  Some of these are mentioned below. To learn more about the
``Request`` and ``Response`` (and different ``Response`` classes), see the
:ref:`HttpFoundation component documentation <component-http-foundation-request>`.

Accessing Configuration Values
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To get the value of any :ref:`configuration parameter <configuration-parameters>`
from a controller, use the ``getParameter()`` helper method::

    // ...
    public function index(): Response
    {
        $contentsDir = $this->getParameter('kernel.project_dir').'/contents';
        // ...
    }

Returning JSON Response
~~~~~~~~~~~~~~~~~~~~~~~

To return JSON from a controller, use the ``json()`` helper method. This returns a
``JsonResponse`` object that encodes the data automatically::

    use Symfony\Component\HttpFoundation\Response;
    // ...

    public function index(): Response
    {
        // returns '{"username":"jane.doe"}' and sets the proper Content-Type header
        return $this->json(['username' => 'jane.doe']);

        // the shortcut defines three optional arguments
        // return $this->json($data, $status = 200, $headers = [], $context = []);
    }

If the :doc:`serializer service </serializer>` is enabled in your
application, it will be used to serialize the data to JSON. Otherwise,
the :phpfunction:`json_encode` function is used.

Streaming File Responses
~~~~~~~~~~~~~~~~~~~~~~~~

You can use the :method:`Symfony\\Bundle\\FrameworkBundle\\Controller\\AbstractController::file`
helper to serve a file from inside a controller::

    use Symfony\Component\HttpFoundation\Response;
    // ...

    public function download(): Response
    {
        // send the file contents and force the browser to download it
        return $this->file('/path/to/some_file.pdf');
    }

The ``file()`` helper provides some arguments to configure its behavior::

    use Symfony\Component\HttpFoundation\File\File;
    use Symfony\Component\HttpFoundation\ResponseHeaderBag;
    // ...

    public function download(): Response
    {
        // load the file from the filesystem
        $file = new File('/path/to/some_file.pdf');

        return $this->file($file);

        // rename the downloaded file
        return $this->file($file, 'custom_name.pdf');

        // display the file contents in the browser instead of downloading it
        return $this->file('invoice_3241.pdf', 'my_invoice.pdf', ResponseHeaderBag::DISPOSITION_INLINE);
    }

Final Thoughts
--------------

In Symfony, a controller is usually a class method which is used to accept
requests, and return a ``Response`` object. When mapped with a URL, a controller
becomes accessible and its response can be viewed.

To facilitate the development of controllers, Symfony provides an
``AbstractController``.  It can be used to extend the controller class allowing
access to some frequently used utilities such as ``render()`` and
``redirectToRoute()``. The ``AbstractController`` also provides the
``createNotFoundException()`` utility which is used to return a page not found
response.

In other articles, you'll learn how to use specific services from inside your controller
that will help you persist and fetch objects from a database, process form submissions,
handle caching and more.

Keep Going!
-----------

Next, learn all about :doc:`rendering templates with Twig </templates>`.

Learn more about Controllers
----------------------------

.. toctree::
    :hidden:

    templates

.. toctree::
    :maxdepth: 1
    :glob:

    controller/*

.. _`Symfony Maker`: https://symfony.com/doc/current/bundles/SymfonyMakerBundle/index.html
.. _`unvalidated redirects security vulnerability`: https://cheatsheetseries.owasp.org/cheatsheets/Unvalidated_Redirects_and_Forwards_Cheat_Sheet.html
