Java Ipify
============

An unofficial client library for `ipify <http://www.ipify.org/>`_: *A Simple IP
Address API*.

Meta
----

- Author: Steven Jeffries
- Email: stevenjeffries@gmail.com
- Status: maintained, active


Purpose
-------

This library makes getting your public ip address from Java extremely simple using ipify's api.

Installation
------------

To install ``JavaIpify``, simply include the jar in your classpath.

Usage
-----

Using this library is very simple.  Here's a simple example:

.. code-block:: java

    import org.ipify.Ipify;
    public class HelloIP {
        public static void main(String[] args) {
            System.out.println(Ipify.getPublicIp());   
        }
    }

Change Log
----------

All library changes, in descending order.

Version 1.0.0
*************

**Released June 2, 2015.**

- First release!
