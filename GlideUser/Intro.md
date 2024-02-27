# GlideUser Introduction

The GlideUser API provides access to information about the current user and current user roles. Using the GlideUser API avioids the need to use the slower GlideRecord queries to get user information.

## Code -> check if user has ITIL role

` var hasITIL = g_user.hasRole('itil');
    if(!hasITIL) {
        alert('You do not have sufficient privileges');
    }