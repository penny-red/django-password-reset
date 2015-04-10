Signals
=======

``password_reset.signals.user_recovers_password``
-------------------------------------------------

providing_args=['user', 'request']

This signal is sent after a user successfully recovers their password. It
provides the ``user`` instance as well as the ``request`` object from the
view.
