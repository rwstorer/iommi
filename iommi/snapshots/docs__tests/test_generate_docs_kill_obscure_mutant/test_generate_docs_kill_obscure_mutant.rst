
# NOTE: this file is automatically generated

from iommi import *
from iommi.admin import Admin
from iommi.struct import Struct
from django.urls import (
    include,
    path,
)
import pytest
from django.db import models
from tests.helpers import req, user_req, staff_req, show_output
from docs.models import *

pytestmark = pytest.mark.django_db

@pytest.fixture(autouse=True)
def auto_use(big_discography):
    pass

request = req('get')


# language=rst
"""
    
Foo
===

Base class: `RefinableObject`

"""
def test_base():
    # language=rst
    """
    """

    # language=rst
    """

Refinable members
-----------------


`name`
^^^^^^

Default: `lambda X: X, # noqa: N803`
    See :ref:`name <name>`


    """
